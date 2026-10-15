# CareSync Health Network — Metadata-Driven Data Platform on Azure & Databricks

An end-to-end data engineering project for a healthcare network, integrating PostgreSQL and CSV data sources using Azure Data Factory and transforming data through the Bronze, Silver, and Gold layers in Databricks.

## Architecture

![CareSync Azure Data Engineering Architecture](assets/architecture-overview.png)

## Data Flow

- **Ingestion:** Azure Data Factory with metadata-driven pipelines.
- **Transformation:** Azure Databricks, PySpark, and Delta Lake using Bronze, Silver, and Gold layers.
- **Control & Auditing:** Azure SQL Database for metadata, watermarks, and audit logs.
- **Security:** Azure Key Vault and Unity Catalog.
- **Notifications:** Azure Logic Apps for automated success and failure emails.
- **CI/CD:** GitHub integration for Azure Data Factory and Databricks.
- **Analytics:** Databricks AI/BI Dashboards, Genie Agents, and Genie ONE.

## Key Features

- Reusable metadata-driven pipelines.
- Full and incremental data loading.
- Delta Lake transformations and Gold-layer reporting tables.
- Automated audit logging and email notifications.
- Secure access and GitHub-based CI/CD workflows.

## Tech Stack

Azure Data Factory · Azure Data Lake Storage Gen2 · Azure SQL Database · Azure Databricks · PySpark · Delta Lake · PostgreSQL · Azure Key Vault · Logic Apps · Unity Catalog · GitHub

## Repositories

- **Azure Data Factory:** https://github.com/rohitmalode/caresync
- **Azure Databricks:** https://github.com/rohitmalode/caresync-Databricks-CI-CD

## Learning & Acknowledgment

This project helped me gain hands-on experience with metadata-driven pipelines, incremental ingestion, PySpark transformations, Medallion Architecture, auditing, secure data access, and CI/CD.

**Thanks to [DataBeli](https://github.com/databeli/caresync_azure_project)** for the tutorial and project guidance.
