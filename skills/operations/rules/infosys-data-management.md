---
title: "Data Management"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: data, frameworks, management, operations, quantitative, technology
---

**Data Warehouse**: Centralized repository of integrated, clean data for analytics.
- Organized for analysis (dimensional modeling, star schemas)
- Historical data retained for trends
- Separate from operational systems to avoid performance impact

**Data Lake**: Large repository of raw, unstructured data.
- Flexible for new analytics use cases
- Requires governance to prevent becoming data swamp

**ETL (Extract-Transform-Load)**: Process for loading data into warehouse/lake.
- Extract: Pull data from operational systems
- Transform: Clean, validate, aggregate, combine
- Load: Move into warehouse/lake

**Master Data Management (MDM)**: Single source of truth for key data (customers, products, suppliers).
- Prevents inconsistencies when same data managed in multiple systems
