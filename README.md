Atlikon–Sports Bar Data Integration & Lakehouse Modernization
📌 Project Overview

Following the acquisition of Sports Bar, a fast-growing sports nutrition and energy bar company, Atlikon faced significant data integration challenges. While Atlikon operated on a structured, data-driven analytics ecosystem, Sports Bar relied on fragmented spreadsheets, shared drives, and inconsistent reporting mechanisms.

This project modernizes and integrates Sports Bar's data into Atlikon's enterprise analytics platform using a Databricks Lakehouse Architecture and Medallion Design Pattern, enabling unified reporting, governance, and business intelligence across both organizations.

🎯 Business Problem
❌ Inconsistent sales and revenue metrics across organizations
❌ Different reporting cycles and business definitions
❌ Data scattered across spreadsheets and shared drives
❌ Lack of centralized governance and data quality controls
❌ No scalable analytics architecture for future growth

✅ Solution
Built a scalable end-to-end data engineering pipeline that:
Standardizes Sports Bar data into a structured format
Aligns reporting metrics with Atlikon's enterprise standards
Supports both historical and incremental data processing
Enables consolidated analytics across parent and child companies
Provides BI-ready datasets for dashboards and AI-driven insights


🏅 Medallion Architecture

🥉 Bronze Layer
Raw data ingestion zone.
Stores source data as-is
Receives files from Amazon S3
Maintains auditability and traceability
Preserves historical records

🥈 Silver Layer
Data cleansing and transformation layer.
Data validation
Schema standardization
Deduplication
Data quality checks
Business rule implementation

🥇 Gold Layer
Business-ready analytics layer.
Aggregated datasets
Reporting-ready tables
Dashboard consumption
AI-powered analysis via Genie
