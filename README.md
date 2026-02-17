# End-to-End Data Engineering Project using Databricks

## Overview
This project is an end-to-end data engineering pipeline built using Databricks (Free Edition) based on a real-world FMCG acquisition scenario. It simulates how a large retail company integrates data from a smaller acquired company into a unified analytics platform.

The project demonstrates modern ETL design, scalable Spark processing, and cloud-based data workflows. This was completed as a weekend hands-on learning project.

---

## Business Scenario
A large FMCG retailer acquires a smaller company. Both organizations store their data in different formats and systems. The objective is to:

- Merge datasets from multiple sources
- Standardize schemas
- Clean and transform raw data
- Build analytics-ready tables
- Enable unified reporting

---

## Architecture
The pipeline follows a Medallion Architecture:

**Bronze Layer**  
Raw data ingestion from source systems

**Silver Layer**  
Cleaned and transformed datasets

**Gold Layer**  
Business-ready aggregated tables

This layered architecture ensures scalability, data quality, and traceability.

---

## Tech Stack
- Databricks Community Edition
- Apache Spark (PySpark)
- Delta Lake
- AWS S3
- SQL
- Python

---

## Features
- Cloud-based data ingestion
- Schema harmonization
- Data cleaning and transformation
- Bronze → Silver → Gold architecture
- Delta Lake storage
- Scalable Spark processing

---

## Workflow
1. Ingest raw acquisition data into Bronze layer  
2. Clean and standardize data in Silver layer  
3. Build curated business tables in Gold layer  
4. Store results using Delta Lake  
5. Enable downstream analytics

---

## Learning Outcomes
- Designing ETL pipelines
- Spark processing in Databricks
- Cloud storage integration
- Data modeling best practices
- Medallion architecture implementation

---

## Future Improvements
- Workflow orchestration
- Streaming data integration
- Data quality validation
- Analytics dashboards
- CI/CD pipeline

---
