
# 🏪 Laxmi Traders Billing App – DevOps Enabled Project

## 📌 Project Overview

Laxmi Traders Billing App is an Android-based billing system developed for a wholesale grocery shop.
This project was extended with a **complete DevOps pipeline** to demonstrate modern CI/CD, containerization, orchestration, and monitoring practices.

---

# 🛠 Tech Stack

### Development

- Android (Java)
- Android Studio

### DevOps Tools

- Git
- GitHub
- GitHub Actions
- Docker
- Kubernetes (Minikube)
- Prometheus
- Grafana

---

# ⚙ DevOps Architecture

Developer pushes code → CI/CD pipeline builds APK → Docker container builds environment → Kubernetes deploys monitoring stack → Prometheus collects metrics → Grafana visualizes metrics.

```
Developer
   ↓
Git Push
   ↓
GitHub Repository
   ↓
GitHub Actions CI/CD
   ↓
Build APK Artifact
   ↓
Docker Container
   ↓
Kubernetes Cluster
   ↓
Prometheus Monitoring
   ↓
Grafana Dashboard
```

---

# 🚀 CI/CD Pipeline

Implemented automated pipeline using **GitHub Actions**.

### Workflow Steps

1. Code pushed to GitHub
2. CI pipeline triggers
3. Gradle builds Android APK
4. APK artifact stored in GitHub Actions
5. Docker image build environment created

---

# 🐳 Containerization

Docker is used to ensure a reproducible build environment.

Example Docker build:

```
docker build -t laxmi-traders-app .
```

---

# ☸ Kubernetes Deployment

Monitoring stack deployed using **Helm** on Kubernetes (Minikube).

Components deployed:

- Prometheus Server
- Alertmanager
- Node Exporter
- Pushgateway
- Grafana Dashboard

---

# 📊 Monitoring

### Prometheus

Collects metrics from Kubernetes cluster.

Access:

```
http://localhost:9090
```

### Grafana

Visualizes metrics using dashboards.

Access:

```
http://localhost:3000
```

Default login:

```
admin / admin
```

---

# 📈 Skills Demonstrated

- CI/CD Pipeline Implementation
- Containerization with Docker
- Kubernetes Orchestration
- Monitoring and Observability
- Infrastructure Automation

---

# 👨‍💻 Author

Shivshankar Kasapnor
DevOps & Software Engineering Enthusiast
=======
📞 Contact
9503127404
shivk202vapm@gmail.com


# LaxmiTraders-BillingApp

App Link: https://drive.google.com/file/d/1sgQdeAzDWy4MkM7hq699XmVCBif6Fdiq/view?usp=sharing

An **offline Android billing application** designed for wholesale grocery shops.  
Built with **Java** in **Android Studio**, it enables fast, professional, and internet-free billing.

---

## 🚀 Features
- **Product Management**
  - Add, edit, delete products with prices and units.
  - Support for multiple units: kg, half kg, dz, half dz, carton, bag.
- **Billing**
  - Add items to cart with quantity and rate editing.
  - Automatic total calculation.
  - Default quantity set to 1 for fast billing.
- **Invoice Generation**
  - Generate professional PDF invoices (79.5±0.5mm width for thermal printers).
  - Customer name right-aligned in the bill.
  - Bold totals and clean table layout.
- **Printing & Sharing**
  - Direct Bluetooth thermal printer support.
  - Send invoice PDF to WhatsApp automatically.
- **Sales & Records**
  - Save and view customer billing history.
  - Filter bills by date range.
  - Export billing history to Excel/PDF.
  - Sales summary charts (daily, weekly, monthly, top products).
- **Backup & Restore**
  - Daily automatic database backup.
  - Restore from backup to prevent data loss.

---

## 🛠 Tech Stack
- **Language:** Java
- **IDE:** Android Studio
- **Database:** SQLite
- **Libraries:**
  - MPAndroidChart (sales charts)
  - Apache POI (Excel export)
  - Android PDFDocument API (PDF invoices)
 
  - ## 📸 Screenshots
 
 
  - ![IMG-20250814-WA0016](https://github.com/user-attachments/assets/541e4a69-ec35-4ab9-9280-7c57aa69bacf)
  - ![IMG-20250814-WA0014](https://github.com/user-attachments/assets/d9489aae-3bc2-4562-bf02-8f3bdd92ffcd)
  - ![IMG-20250814-WA0015](https://github.com/user-attachments/assets/3bb6153d-b151-4bca-b8eb-573ea7eef334)
  - ![IMG-20250814-WA0010](https://github.com/user-attachments/assets/ee4b2f14-2e0f-47e2-bdbf-c102bc0a5f9c)
  - ![IMG-20250814-WA0017](https://github.com/user-attachments/assets/f41259a0-e7d3-4cd7-ab49-f003db48fd47)
  - ![IMG-20250814-WA0013](https://github.com/user-attachments/assets/595c6284-2840-4237-a176-694d241fd8af)
  - ![IMG-20250814-WA0009](https://github.com/user-attachments/assets/7863fee6-992a-4153-9d4c-9ddb2dba90a3)
>>>>>>> billing_app/main
