# Serhii Yashchuk

### Marketing data engineering · Web analytics to warehouse models

I build marketing data platforms that connect website events, advertising and CRM data — from tracking implementation to data pipelines, warehouse models and reporting for business decisions.

My background is in web analytics. I work across the full cycle: deciding what to measure, validating collection, connecting sources and building the datasets and metrics needed for analysis.

### From business questions to usable data

| Stage | What I work on |
| --- | --- |
| **Measure** | Event specifications, parameters, conversion definitions and GA4/GTM implementation or troubleshooting |
| **Connect** | API ingestion from analytics, advertising platforms, CRMs and spreadsheets |
| **Model** | Python/SQL pipelines, BigQuery or PostgreSQL, Dataform/dbt models, checks and recovery workflows |
| **Analyse** | Consistent metrics, funnel and marketing reporting, documentation and handover |

### Selected work

- **[Agency reporting automation](https://www.upwork.com/freelancers/~014d4b1d7430018c18?p=2110854476408225792)** — scheduled BigQuery processing to replace recurring manual exports.
- **[End-to-end marketing analytics](https://www.upwork.com/freelancers/~014d4b1d7430018c18?p=1879962943442882560)** — advertising, CRM outcomes and tracking across 10 websites, connected in BigQuery and Looker Studio.
- **[Clickstream modeling](https://www.upwork.com/freelancers/~014d4b1d7430018c18?p=1721750854095478784)** — Python, PostgreSQL and dbt, with date-range recovery, run locking and failure alerts.
- **[E-commerce measurement](https://www.upwork.com/freelancers/~014d4b1d7430018c18?p=2037061713996271616)** — maintained tracking across three domains and 13 advertising and affiliate platforms.

Case links open my Upwork portfolio.

### Runnable engineering demos

These five repositories use **synthetic data only**. They are focused, reproducible demos and templates, not client source code or production deployments. Each README documents its tested scope and limitations.

1. **[Marketing data reconciliation](https://github.com/zoercalm/marketing-data-reconciliation)** — compare daily totals, distinguish missing rows from numerical differences, and produce actionable reports. CSV inputs only; no live source connections or automatic repairs.
2. **[Clickstream journeys with PostgreSQL and dbt](https://github.com/zoercalm/clickstream-dbt-postgres)** — cart-entry paths, daily range reloads and validated batch resumption. Synthetic source; raw and reporting are not published atomically.
3. **[GA4 / GTM event taxonomy](https://github.com/zoercalm/ga4-gtm-event-taxonomy)** — a commerce event contract, payload validator and browser dataLayer demo. No GTM container, GA4 property or live collection is configured.
4. **[ClickHouse mart publishing](https://github.com/zoercalm/metrika-clickhouse-release-pipeline)** — dbt checks before publication and journaled recovery. The consistency guarantee covers one completed mart, not all raw tables together; rollback remains experimental and is not crash-safe.
5. **[Synthetic keyword-demand modelling](https://github.com/zoercalm/google-ads-bigquery-dataform-template)** — local ingestion, revision handling and compile-tested BigQuery/Dataform assets. Google Ads API and BigQuery execution are not included; this models search demand, not campaign spend or conversions.

### Tools

Python · SQL · BigQuery · PostgreSQL · Dataform · dbt · GA4 · Google Tag Manager · Looker Studio

Commercial source repositories remain private. The portfolio cases describe selected work without exposing client code or datasets. The demos above are synthetic examples; other public labs may be learning projects or forks.

[Work with me on Upwork](https://www.upwork.com/freelancers/~014d4b1d7430018c18)

[Connect on LinkedIn](https://www.linkedin.com/in/serhii-yashchuk/)
