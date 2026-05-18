# 🛒 E-commerce Lakehouse Pipeline (Medallion Architecture)
# High-Throughput Apache Spark Structured Streaming Optimization in Resource-Constrained Edge and Cloud Environments
#### Lalit  Jindal  2210991847
#### Monu kumar     2210990583
#### Status         Pending to communicate in conference
This project implements an **end-to-end data pipeline** for an e-commerce system using the **Medallion Architecture (Bronze → Silver → Gold)** on **Databricks (PySpark + Delta Lake)**.

It is designed to be **scalable, metadata-driven, and production-ready**, supporting incremental processing, auditing, and orchestration.

---

## 📌 Project Overview

The pipeline processes raw e-commerce data through multiple layers:

- **Bronze Layer** → Raw ingestion
- **Silver Layer** → Data cleaning + transformation
- **Gold Layer** → Business KPIs & analytics
- **Orchestration** → End-to-end workflow execution

---

## 🏗️ Architecture

Raw Data Sources → Bronze → Silver → Gold → Analytics

---

## 📂 Project Structure

ecommerce_lakehouse/
├── bronze/
│   └── 01_bronze_ingestion.py
├── silver/
│   ├── 02_silver_cleaning.py
│   └── 03_silver_dim_fact.py
├── gold/
│   └── 04_gold_kpis.py
├── config/
│   └── 00_setup_metadata.py
├── orchestration/
│   └── 05_pipeline_orchestration.py

---

## ⚙️ Key Features

### Metadata-Driven Pipeline
- Central metadata table
- Supports incremental/full loads

### Bronze Layer
- Raw ingestion with metadata columns
- Delta format storage

### Silver Layer
- Data cleaning, deduplication
- Dimensional modeling

### Gold Layer
- Business KPIs like revenue, orders, AOV

### Orchestration
- End-to-end pipeline execution

---

## 🧰 Tech Stack

- Databricks
- PySpark
- Delta Lake
- SQL
- Python

---

## 🚀 How to Run

1. Run metadata setup  
2. Execute orchestration pipeline  

---

## 📊 Example Output

| order_date | total_revenue | total_orders |
|------------|--------------|-------------|
| 2025-01-01 | 50000        | 120         |

---

## 👨‍💻 Author

Lalit Jindal
