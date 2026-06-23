# Zoney B2B Motor Parts Asset Management Platform

## Overview

Zoney is an end-to-end Data Engineering project built on Databricks using a Medallion Architecture (Bronze → Silver → Gold).

The platform ingests motor-parts data from multiple legacy sources, applies business validation rules, enriches data with financial and compliance logic, and produces AI-powered analytics for business users.

---

## Business Problem

Motor-parts companies often receive data from multiple systems including:

- DB2 Mainframe
- SQL Server
- Excel Files

This creates challenges such as:

- Data quality issues
- Duplicate records
- Tax compliance risks
- Vendor management problems
- Warranty liability tracking
- Slow reporting processes

Zoney solves these problems through an automated Lakehouse architecture.

---

## Architecture

Bronze → Silver → Silver Enhancements → Gold

### Bronze Layer
- Raw CSV ingestion
- Incremental processing
- Watermarking
- Delta tables

### Silver Layer
- Star schema creation
- Data cleansing
- Standardization
- 50+ validation rules

### Silver Enhancements
- Tax calculations
- Use-tax liability
- Warranty reserve management
- Vendor risk scoring
- End-of-Life (EOL) margin protection

### Gold Layer
- Monthly sales cubes
- Vendor scorecards
- Customer segmentation
- Revenue forecasting
- Anomaly detection

---

## Technologies Used

- Databricks
- Apache Spark
- PySpark
- Spark SQL
- Delta Lake
- Python
- Pandas
- Faker
- Machine Learning

---

## Dataset

Synthetic datasets generated using Python:

| Dataset | Records |
|----------|---------|
| Customers | 8,000 |
| Vendors | 150 |
| Manufacturers | 75 |
| Products | 1,000 |
| Transactions | 50,000 |
| Price History | 3,000+ |

Total records processed:

62,000+

---

## Key Business Rules

### Tax Compliance
- Texas Sales Tax Validation
- Use-Tax Detection
- Tax Nexus Evaluation

### Vendor Compliance
- Vendor License Validation
- Vendor Risk Scoring

### Financial Controls
- Warranty Reserve Accrual
- Margin Protection Rules

### Operations
- Duplicate Billing Detection
- Credit Limit Enforcement
- B2B Minimum Order Validation

---

## AI Features

### Customer Segmentation
RFM-based customer classification:

- Champions
- Loyal Customers
- At Risk Customers

### Revenue Anomaly Detection
Z-score based anomaly detection.

### Demand Forecasting
3-Month Category Revenue Forecast using Linear Regression.

---

## Logging & Monitoring

Pipeline logging captures:

- Run ID
- Layer Name
- Start Time
- End Time
- Status
- Records Processed
- Error Messages

---

## Project Deliverables

✅ Bronze Layer

✅ Silver Layer

✅ Gold Layer

✅ Incremental Ingestion

✅ Watermarking

✅ Data Quality Framework

✅ AI Analytics

✅ Vendor Risk Scoring

✅ Tax Compliance Framework

✅ Automated Logging

---

## Skills Demonstrated

- Data Engineering
- ETL Development
- Data Modeling
- Data Governance
- Data Quality
- Spark Optimization
- Delta Lake
- Business Intelligence
- Machine Learning
- Cloud Data Platforms

---

## Author
Zara

Master's in Cybersecurity

Databricks | Spark | Python | SQL | Data Engineering
