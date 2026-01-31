# Fraud Audit ELT Pipeline (Azure Data Factory)

## Overview
This repository contains the Azure Data Factory (ADF) ELT pipeline used to
ingest, clean, and curate credit card transaction data for downstream analytics
and machine learning.

The pipeline follows a Medallion Architecture (Bronze → Silver) and publishes
analysis-ready datasets to Azure Data Lake Storage Gen2.

## Architecture
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Bronze and Silver layers

## Output
The Silver layer produced by this pipeline is consumed by the
Fraud Detection ML project:
➡️ https://github.com/MusaIP12/fraud-audit-ml_detection

## Scope
- Data ingestion
- Data validation
- Data standardisation


