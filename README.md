# Azure Databricks Data Engineering Project

## Overview

This project demonstrates an end-to-end data engineering pipeline built using
Azure Databricks and Azure Data Lake Storage Gen2.

The project covers data ingestion, transformation, data quality, data
governance, and analytics using modern Databricks and Azure technologies.

## Architecture

The project follows a Medallion Architecture:

- Bronze - Raw ingested data
- Silver - Cleaned and transformed data
- Gold - Business-ready analytical data

## Technologies

- Azure Databricks
- Azure Data Lake Storage Gen2
- Apache Spark
- PySpark
- SQL
- Delta Lake
- Unity Catalog
- GitHub
- Lakflow Jobs

## Project Structure

```text
setup/          - Databricks and Unity Catalog setup scripts
notebooks/      - Data engineering notebooks
sql/            - SQL queries
tests/          - Data quality and validation tests
docs/           - Architecture and project documentation