---
title: "Data Architecture"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: architecture, data, technology
---

**Modern Data Stack**:

```
Data Sources → Ingestion → Data Lake/Warehouse → 
  Transformation → Analytics/BI → Consumption (Apps, Reports, ML)
```

**Cloud Data Warehouses** (Snowflake, BigQuery, Redshift):
- Separate compute and storage for cost efficiency
- Native support for unstructured data
- Built-in analytics and ML capabilities

**Data Lakes vs Data Warehouses**:
- Lakes store raw data; warehouses store structured, processed data
- Modern approach: lakehouse platforms combining benefits
- Medallion architecture (bronze → silver → gold) ensures data quality progression

**ELT vs ETL**:
- **ELT**: Load raw data first, transform in warehouse (faster, flexible)
- **ETL**: Transform before loading (more control, higher latency)
- Modern stacks favor ELT for agility
