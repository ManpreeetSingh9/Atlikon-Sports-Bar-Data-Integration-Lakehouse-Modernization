# Atlikon–Sports Bar Enterprise Data Engineering & Analytics Modernization Platform

## 📌 Project Overview

Atlikon's acquisition of Sports Bar introduced significant data integration challenges due to fragmented data sources, inconsistent reporting standards, and disconnected analytics processes.

This project implements a Databricks-based data engineering platform that consolidates, transforms, and governs enterprise data using the Medallion Architecture. The solution delivers automated data pipelines, unified reporting, and scalable analytics across both organizations.

---

## 🎯 Business Challenges

▸ Inconsistent sales and revenue metrics across organizations

▸ Different reporting cycles and business definitions

▸ Data scattered across spreadsheets and shared drives

▸ Lack of centralized data governance and quality controls

▸ Limited scalability for future analytics and reporting needs
---

## ✅ Solution

Designed and implemented an end-to-end data engineering platform that:

✔ Standardized Sports Bar data into enterprise-ready formats

✔ Aligned business metrics with Atlikon's reporting standards

✔ Supported both historical and incremental data processing

✔ Enabled consolidated analytics across parent and child companies

✔ Delivered BI-ready datasets for reporting and AI-driven insights

✔ Established a scalable Databricks-based architecture for future growth

---


## 🏗️ Architecture Overview

The solution leverages a Databricks Lakehouse Architecture with the Medallion Design Pattern to integrate Sports Bar data into Atlikon's enterprise analytics platform.

![image alt](https://github.com/ManpreeetSingh9/atlikon-sports-bar-data-integration-pipeline-and-analytics/blob/56ad12b8d563273fceeee572a1e8a841e63b588b/3_resources/architecture.png)
### Key Components

* **Amazon S3** serves as the landing zone for raw source files and archive storage.
* **Databricks Lakeflow Jobs** orchestrate automated ingestion and transformation workflows.
* **Bronze Layer** stores raw ingested data for auditability and traceability.
* **Silver Layer** applies data cleansing, validation, standardization, and business rules.
* **Gold Layer** provides curated, business-ready datasets for analytics and reporting.
* **Unity Catalog** enables centralized governance, security, and data lineage management.
* Child company gold datasets are integrated into **parent company analytics tables** for unified reporting.
* **Databricks Dashboards** and **Genie** provide business intelligence and AI-powered data exploration.

### Processing Strategy

* **Historical Backfill (July–November):** One-time batch migration of legacy Sports Bar data.
* **Incremental Loads (December onwards):** Automated daily processing of new and updated records through Databricks workflows.

## ⚙️ Workflow Orchestration
![image alt](https://github.com/ManpreeetSingh9/atlikon-sports-bar-data-integration-pipeline-and-analytics/blob/56ad12b8d563273fceeee572a1e8a841e63b588b/3_resources/orchestration.png)
Databricks Workflows and Jobs automate the end-to-end pipeline by:

* Scheduling data ingestion from Amazon S3
* Triggering PySpark transformation pipelines
* Managing incremental load processing
* Monitoring job execution and failures
* Automating data movement across Medallion layers
* Ensuring reliable and scalable pipeline execution
---

## 🛠️ Technology Stack

## 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| ⚙️ Data Engineering | Databricks |
| ⚙️ Data Processing | Apache Spark (PySpark) |
| ⚙️ Programming | Python |
| ⚙️ Querying | SQL |
| ☁️ Cloud Storage | Amazon S3 |
| 🔄 Orchestration | Databricks Workflows |
| 🏗️ Architecture | Medallion Architecture |
| 🔐 Governance | Unity Catalog |
| 📊 Visualization | Databricks Dashboards |

---
## 📈 Repository Directory Structure

![image alt](https://github.com/ManpreeetSingh9/atlikon-sports-bar-data-integration-pipeline-and-analytics/blob/56ad12b8d563273fceeee572a1e8a841e63b588b/3_resources/repository.png)

---
## 📈 Key Outcomes

* Unified reporting across Atlikon and Sports Bar
* Improved data quality and governance
* Automated historical and incremental data processing
* Scalable Lakehouse architecture supporting future acquisitions
* Faster access to trusted business insights
* Reduced manual reporting effort through automation
* Established a foundation for AI-driven analytics and decision-making
