# Hi, I'm Sai Sri Ram Tammineedi

**Data Engineer** — Snowflake | dbt | Advanced SQL

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

I build end-to-end data pipelines using Snowflake and dbt. I design dimensional models, write production-grade analytical SQL, and create data marts that directly answer business questions.

---

## Core Skills

**Snowflake:** Virtual warehouses, COPY INTO, Time Travel, Streams & Tasks, QUALIFY, PIVOT, Window Functions (LAG/LEAD, NTILE, RANK, ROWS BETWEEN), LISTAGG, ARRAY_AGG, Dynamic Data Masking, Snowpipe, Zero-copy Clone, ASOF JOIN

**dbt:** Staging/Marts layered modeling, ref()/source() macros, Incremental models, Snapshots (SCD-2), Custom macros, Generic + Singular tests, dbt_utils, dbt docs

**SQL:** CTEs, Recursive CTEs, Window functions, Conditional aggregation, RFM segmentation, Cohort analysis, Date spines

---

## Projects

### E-Commerce Analytics (Snowflake + dbt)
Dataset: Kaggle Brazilian E-Commerce (Olist) — 100k+ orders

Full ELT pipeline: CSV → Snowflake stage → Raw → Staging (dbt views) → Marts (dbt tables). 7 business questions answered including MoM revenue trends, on-time delivery rates, customer retention.

Repo: [snowflake-ecommerce-analytics](https://github.com/sriramlpu/snowflake-ecommerce-analytics)

---

### Retail Sales Analytics + RFM Segmentation (Snowflake + dbt)
Dataset: Kaggle Sample Superstore — 10k US retail orders

Star schema model. RFM customer segmentation with NTILE(5) on Recency/Frequency/Monetary. Discount erosion analysis (>30% discount = negative margin). State-level revenue vs profit analysis.

Repo: [snowflake-retail-sales-dbt](https://github.com/sriramlpu/snowflake-retail-sales-dbt)

---

### HR Analytics + Attrition Risk Scoring (Snowflake + dbt)
Dataset: Kaggle IBM HR Employee Attrition — 1,470 employees

Composite attrition risk score (0-10). NTILE salary quartile analysis: Q1 earners churn at 26% vs Q4 at 8%. Promotion gap analysis: 5+ years without promotion = 2x attrition. Department KPIs via window functions.

Repo: [snowflake-hr-analytics-dbt](https://github.com/sriramlpu/snowflake-hr-analytics-dbt)
