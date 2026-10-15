# CareSync Health Network — Metadata-Driven Data Platform on Azure & Databricks

An end-to-end healthcare data engineering project that integrates PostgreSQL and CSV data sources using Azure Data Factory and transforms data through the **Bronze, Silver, and Gold Medallion Architecture** in Databricks.

## Architecture

![CareSync Architecture](assets/architecture-overview.png)

## Data Flow

- **Data Sources:** PostgreSQL and CSV files in Azure Blob Storage.
- **Data Ingestion:** Metadata-driven pipelines using Azure Data Factory (ADF).
- **Data Transformation:** Azure Databricks, PySpark, and Delta Lake.
- **Control & Auditing:** Azure SQL Database for metadata, watermarks, and audit logs.
- **Governance & Security:** Unity Catalog, Azure Key Vault, and managed identities.
- **Notifications:** Azure Logic Apps for automated success and failure emails.
- **CI/CD:** GitHub integration for ADF and Databricks.
- **Consumption:** Databricks AI/BI Dashboards, Genie Agents, and Genie ONE.

## Key Features

- Reusable, metadata-driven data pipelines.
- Full and incremental data loading.
- Bronze, Silver, and Gold data processing.
- Automated audit logging and email notifications.
- Secure data access and GitHub-based CI/CD workflows.
- Gold-layer reporting tables for analytics.

## Tech Stack

Azure Data Factory · Azure Data Lake Storage Gen2 · Azure SQL Database · Azure Databricks · PySpark · Delta Lake · PostgreSQL · Azure Key Vault · Logic Apps · Unity Catalog · GitHub

## Repositories

- **Azure Data Factory (ADF):** https://github.com/rohitmalode/caresync
- **Azure Databricks:** https://github.com/rohitmalode/caresync-Databricks-CI-CD

## Learning & Acknowledgment

This project helped me gain hands-on experience with metadata-driven pipelines, incremental ingestion, PySpark transformations, Medallion Architecture, auditing, secure data access, and CI/CD workflows.

**Special thanks to [DataBeli](https://github.com/databeli/caresync_azure_project)** for the tutorial, project structure, and guidance throughout this learning journey.
