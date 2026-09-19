# Daily Express Analytics Automation

> **End-to-End Business Analytics, Data Quality & Automated Reporting System**

**Form Submission → Data Storage → Data Cleaning → Validation → Analytics → Interactive Dashboard → CSV Dataset → Automated Email Reporting**

---

## 📌 Project Overview

**Daily Express Analytics Automation** is an end-to-end business analytics and reporting automation system built using **n8n, Python, JavaScript, HTML, CSS, Chart.js, Leaflet.js, and n8n Data Tables**.

The system automates the complete analytics lifecycle starting from data collection and storage to data cleaning, validation, duplicate detection, business analysis, interactive visualization, CSV dataset generation, and automated email reporting.

The main goal of this project is to replace repetitive manual reporting activities with an automated and reusable analytics pipeline.

---

# 1. ❓ Why This Project?

Business teams frequently collect operational information through forms, spreadsheets, or internal systems.

However, collecting data is only the beginning. After receiving the data, analysts often need to manually:

- Clean inconsistent data
- Remove unnecessary spaces
- Standardize values
- Check missing fields
- Validate emails and dates
- Detect duplicate records
- Calculate KPIs
- Analyze departments
- Analyze regional/state-wise distribution
- Create charts
- Build dashboards
- Export datasets
- Prepare reports
- Send reports to stakeholders

This manual process can result in:

- Repetitive work
- Delayed reporting
- Data-quality issues
- Higher chances of human error
- Difficulty maintaining consistent reports
- Repeated Excel/CSV processing

This project addresses these problems by automating the complete workflow using **n8n**.

---

# 2. 💡 Proposed Solution

The project creates an automated pipeline that converts raw form submissions into structured business insights.

```text
                    DATA COLLECTION
                         │
                         ▼
                ┌─────────────────┐
                │ Form Submission │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │   Insert Row    │
                └────────┬────────┘
                         │
                         ▼
                  DATA PROCESSING
                         │
                         ▼
                ┌─────────────────┐
                │ Get All Records │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Data Cleaning & │
                │   Validation    │
                └────────┬────────┘
                         │
                         ▼
                    ANALYTICS
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     State-wise      Department      Time Trend
      Analysis        Analysis        Analysis
          │              │              │
          └──────────────┼──────────────┘
                         │
                         ▼
                INTERACTIVE DASHBOARD
                         │
                         ▼
                AUTOMATED REPORTING
                    ┌────┴────┐
                    ▼         ▼
                  CSV       Email
                Dataset     Report
```

# 🖼️ Project Screenshots

## Complete n8n Workflow

![Complete n8n Workflow](./Screenshot%202026-09-20%20032347.png)

---

## 📧 Data Collection & Email Automation

![Data Collection and Email Automation](./Screenshot%202026-09-20%20032353.png)

---

## 📊 Dashboard Analytics Workflow

![Dashboard Analytics Workflow](./Screenshot%202026-09-20%20032430.png)

---

# 🖥️ Dashboard Screenshots

## Dashboard Screenshot 1

![Dashboard Screenshot 1](./Screenshot%202026-09-20%20035259.png)

---

## Dashboard Screenshot 2

![Dashboard Screenshot 2](./Screenshot%202026-09-20%20035311.png)


---

## Dashboard Screenshot 3

![Dashboard Screenshot 3](./Screenshot%202026-09-20%20035332.png)

---

## 🖥️ Dashboard Screenshot 4

![Dashboard Screenshot 4](./Screenshot%202026-09-20%20040403.png)

---

## 🖥️ Dashboard Screenshot 5

![Dashboard Screenshot 5](./Screenshot%202026-09-20%20040722.png)
