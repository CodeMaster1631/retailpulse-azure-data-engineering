
# RetailPulse – Azure Multi-Source Data Engineering Platform

## Project Overview

RetailPulse is an end-to-end data engineering platform built using Microsoft Azure.

The platform simulates a retail and e-commerce company's data ecosystem, integrating multiple independent source systems into a centralized data lake and analytics platform.

## Business Scenario

The business receives data from:

1. E-commerce application – PostgreSQL
2. Payment provider – REST API
3. Logistics provider – SFTP
4. Marketing department – CSV and JSON files
5. ERP system – Batch file exports

The objective is to consolidate these sources and provide reliable business analytics.

## Technology Stack

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Azure Databricks
- Python and PySpark
- PostgreSQL (Neon)
- Azure Key Vault
- Azure Monitor
- GitHub Actions
- Bicep
- Power BI

## Key Engineering Features

- Multi-source data ingestion
- Metadata-driven reusable pipelines
- Outer and inner pipeline orchestration
- Full and incremental loading
- Watermark management
- Bronze, Silver and Gold architecture
- Delta Lake and MERGE operations
- Slowly Changing Dimensions
- Data quality and reconciliation
- Error handling and recovery
- CI/CD and Infrastructure as Code
- Monitoring and operational auditing

## Repository Structure

- source-systems/
- control-database/
- azure-data-factory/
- databricks/
- infrastructure/
- tests/
- docs/
- powerbi/

## Project Status

Initial setup in progress.

## Learning Objective

Demonstrate practical, production-oriented Azure data engineering
skills through an end-to-end, multi-source retail data platform.
