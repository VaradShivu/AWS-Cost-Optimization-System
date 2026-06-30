# AWS Cost Optimization & Intelligent Recommendation System

![PHP](https://img.shields.io/badge/PHP-8.2-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple)
![Chart.js](https://img.shields.io/badge/Chart.js-4-red)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

The **AWS Cost Optimization & Intelligent Recommendation System** is a web-based application developed using **PHP, HTML, CSS, JavaScript, Bootstrap, and Chart.js**. The system analyzes AWS Billing CSV reports, provides cost analytics, forecasts future expenses, detects anomalies, generates optimization recommendations, and presents governance and reporting dashboards.

This project is designed as an academic cloud computing project while demonstrating practical AWS cost analysis concepts.

---

# 🚀 Features

## Authentication

- Secure Login
- Session Management
- Logout
- Protected Pages

---

## Dashboard

- Total AWS Cost
- Average Cost
- Highest Cost Service
- Total Billing Records
- Top Services
- Top Regions
- Interactive Charts

---

## CSV Upload

- Upload AWS Billing CSV
- Automatic Validation
- Replace Existing CSV
- Upload Status

---

## Analytics

- Service-wise Cost Analysis
- Region-wise Cost Analysis
- Monthly Cost Trends
- CPU Usage Analysis
- Storage Analysis
- Request Statistics
- Interactive Graphs

---

## Forecast Module

- Monthly Cost Forecast
- Budget Prediction
- Estimated Savings
- Forecast Charts
- Trend Analysis

---

## Anomaly Detection

- High Cost Detection
- High CPU Detection
- High Storage Detection
- Risk Assessment
- Automatic Recommendations

---

## Recommendation Engine

- Cost Saving Opportunities
- Reserved Instance Suggestions
- Storage Optimization
- EC2 Optimization
- Green Computing Suggestions
- Estimated Savings

---

## Governance

- Compliance Dashboard
- Security Recommendations
- Budget Governance
- Resource Governance
- Governance Violations
- Compliance Charts

---

## Reports

- Executive Summary
- Printable Reports
- Monthly Charts
- Cost Summary
- Governance Summary
- Recommendation Summary

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| PHP 8 | Backend |
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Client-side Logic |
| Bootstrap 5 | Responsive UI |
| Chart.js | Data Visualization |
| Font Awesome | Icons |
| XAMPP | Local Server |

---

# 📂 Project Structure

```
AWS-Cost-Optimization-System
│
├── assets
│   ├── css
│   │   └── style.css
│   └── js
│       └── script.js
│
├── classes
│   └── CsvProcessor.php
│
├── config
│   ├── auth.php
│   └── session.php
│
├── data
│   └── users.json
│
├── uploads
│   └── aws_cost.csv
│
├── login.php
├── logout.php
├── dashboard.php
├── upload.php
├── analytics.php
├── forecast.php
├── anomaly.php
├── recommendation.php
├── governance.php
├── reports.php
│
└── README.md
```

---

# ⚙ Installation

## Step 1

Install **XAMPP**

Download from:

https://www.apachefriends.org/

---

## Step 2

Copy project into

```
C:\xampp\htdocs\
```

Result:

```
C:\xampp\htdocs\AWS-Cost-Optimization-System
```

---

## Step 3

Start

- Apache

(MySQL is **not required**.)

---

## Step 4

Open Browser

```
http://localhost/AWS-Cost-Optimization-System/login.php
```

---

# 🔑 Login Credentials

Username

```
admin
```

Password

```
admin123
```

---

# 👤 Users File

Create

```
data/users.json
```

```json
[
  {
    "username":"admin",
    "password":"admin123",
    "name":"Administrator"
  }
]
```

---

# 📁 Upload CSV

Upload an AWS Billing CSV from

```
Upload CSV
```

The uploaded file is stored as

```
uploads/aws_cost.csv
```

---

# 📊 Workflow

```
Login
      │
      ▼
Dashboard
      │
      ▼
Upload AWS Billing CSV
      │
      ▼
Analytics
      │
      ▼
Forecast
      │
      ▼
Anomaly Detection
      │
      ▼
Recommendations
      │
      ▼
Governance
      │
      ▼
Reports
```

---

# 📈 Dashboard Metrics

- Total Cost
- Average Cost
- Total Records
- Highest Cost Service
- Top Services
- Top Regions

---

# 📊 Charts

- Monthly Cost Trend
- Service Distribution
- Region Distribution
- Governance Score
- Forecast Trend
- Savings Distribution
- Anomaly Summary

---

# 💰 Cost Optimization Recommendations

- EC2 Rightsizing
- Reserved Instances
- Savings Plans
- Glacier Storage
- Delete Unused EBS Volumes
- Auto Scaling
- AWS Budgets
- Cost Allocation Tags

---

# 🔒 Governance Features

- Compliance Monitoring
- Security Recommendations
- Budget Governance
- Resource Governance
- Governance Violations

---

# 📄 Reports

- Executive Summary
- Monthly Cost Report
- Service Cost Report
- Region Report
- Recommendation Summary
- Governance Summary

---

# 🎯 Future Enhancements

- MySQL Database Integration
- User Registration
- Machine Learning Cost Prediction
- Email Notifications
- PDF Report Generation
- AWS Cost Explorer API Integration
- CloudWatch Integration
- Multi-user Support
- Dark Mode
- Export to Excel

---

# 📸 Screenshots

Add screenshots of:

- Login Page
- Dashboard
- Analytics
- Forecast
- Anomaly Detection
- Recommendation Engine
- Governance Dashboard
- Reports

---

# 👨‍💻 Developed By

Project developed as part of an academic cloud computing project.

**Technology Stack**

- PHP
- HTML
- CSS
- JavaScript
- Bootstrap
- Chart.js

---

# 📜 License

This project is developed for educational and academic purposes.

---

## ⭐ Project Highlights

- Responsive Web Application
- Interactive Dashboard
- AWS Billing CSV Analysis
- Cost Forecasting
- Anomaly Detection
- Recommendation Engine
- Governance Dashboard
- Printable Reports
- Modern User Interface
- PHP-Based Implementation
