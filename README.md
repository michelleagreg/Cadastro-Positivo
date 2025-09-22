# Cadastro-Positivo
Large-scale credit data migration with strong governance and BI insights
# 📌 Positive Credit Data Migration & Governance Framework

This repository showcases a real-world case of **data migration, governance, and quality validation** developed for Brazil’s **Positive Credit System (Cadastro Positivo)**.  
The project involved moving massive volumes of sensitive financial data from **legacy platforms to Google Cloud Platform (GCP)**, while implementing a **data quality and governance framework** to ensure accuracy, compliance, and business reliability.

---

## 🚀 Project Overview
- **Objective**: Migrate Brazil’s Positive Credit system data to cloud infrastructure, guaranteeing integrity, governance, and continuous monitoring.  
- **Key Challenge**: Ensure **data accuracy and lineage** while maintaining **regulatory compliance** and **business continuity** during migration.  
- **Outcome**: A trusted, governed, and scalable cloud-based data environment integrated with **BI dashboards** for decision-making.  

---

## 🔧 Tech Stack
- **Cloud & Data Platforms**: Google Cloud Platform (BigQuery, Cloud Storage, Pub/Sub)  
- **Data Transformation & Orchestration**: SQL | dbt | Apache Airflow  
- **Data Governance & Quality**: dbt tests | automated validation | anomaly detection | alerts  
- **Visualization**: Power BI | Looker Studio (KPI dashboards for data quality and business insights)  

---

## 📊 Key Deliverables
- ✅ **Data Migration**: From legacy on-prem systems to GCP BigQuery with zero downtime.  
- ✅ **Governance Framework**: End-to-end data lineage, monitoring, and automated quality checks.  
- ✅ **dbt Data Quality Tests**: Rules for validation of tables, transformations, and critical KPIs.  
- ✅ **Automation & Orchestration**: Airflow DAGs for ingestion, transformation, and daily monitoring.  
- ✅ **BI Dashboards**: Reports for unpaid installments, customer behavior, and data quality metrics.  

---

## 🗂 Repository Structure
├── sql/                # Core SQL scripts for transformations & validation

├── dbt/                # dbt models, tests, and documentation

├── airflow_dags/       # Airflow DAGs for orchestration



├── dashboard/          # Power BI & Looker Studio exports (images, PDFs)

├── data_samples/       # Mock sample data (anonymized)

└── README.md           # Project documentation
