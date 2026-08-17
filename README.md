# E-Commerce Sales & Customer Analytics

An end-to-end e-commerce analytics project built using **Python, Google Colab, Google BigQuery, SQL, and Looker Studio**.

The project uses synthetically generated e-commerce data to simulate a real-world retail environment. The data is loaded into BigQuery, transformed using SQL, and analyzed through an interactive Looker Studio dashboard.

---

## 📌 Project Overview

The goal of this project is to build a complete analytics workflow starting from raw transactional data and ending with an interactive business intelligence dashboard.

The project covers:

- Data generation using Python
- Data processing using Pandas and NumPy
- Cloud data warehousing using Google BigQuery
- SQL-based data transformation
- Creation of analytical views
- Business KPI development
- Interactive dashboard development using Looker Studio
- Product, customer, category, and sales analysis

---

## 🏗️ Project Architecture

```text
┌──────────────────────┐
│      Python          │
│   Pandas + NumPy     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│    Google Colab      │
│ Data Generation &    │
│ Data Processing      │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│    Google BigQuery   │
│                      │
│  customers           │
│  products            │
│  orders              │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│        SQL           │
│ Analytical Views     │
│                      │
│ Monthly Sales        │
│ Product Performance  │
│ Customer Summary     │
│ Category Performance │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│     Looker Studio    │
│ Interactive Dashboard│
└──────────────────────┘
