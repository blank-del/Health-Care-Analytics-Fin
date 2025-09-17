# Finnish Healthcare Analytics - Avohilmo [THL API](https://yhteistyotilat.fi/wiki08/display/THLKA/THL%3An+avoimen+datan+rajapinnan+kuvaus)

This project demonstrates the design and implementation of a data engineering pipeline using Databricks, PySpark, Unity Catalog and GitHub Actions.

The data source is **THL's Avohilmo dataset** (health care outpatient visits by area and muncipality), accessed via their **custom JSON API**. The pipeline follows the **Medallion Architecture** (Bronze -> Silver -> Gold) with scheduled jobs and a dashboard for exploration.

## Architecture
![Medallion Architecture](docs/Healthcare_arch.svg) 

## Tech Stack
- Cloud: Databricks Free Edition
- Languages: Python (PySpark), SQL
- Data Source: THL Avohilmo API
- Architecture: Medallion (Bronze, Silver, Gold)
- Tools: Databricks Jobs, Unity Catalog, Delta Lake
- Visualisation: Databricks dashboard