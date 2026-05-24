# Azure Cybersecurity Lakehouse Platform

An end-to-end modern cybersecurity data engineering project built on Microsoft Azure for scalable threat ingestion, transformation, analytics, and reporting.

This project demonstrates how enterprise cybersecurity logs and threat intelligence data can be processed through a lakehouse architecture using Azure cloud technologies.

## Technologies Used

- Azure Synapse Analytics
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Delta Lake
- Power BI

## Project Overview

The platform is designed to simulate a real-world cybersecurity analytics environment where security events and threat logs are ingested from multiple source systems and processed through a layered lakehouse architecture.

The solution includes:

- Data ingestion pipelines using Azure Data Factory
- Bronze, Silver, and Gold data lake layers
- Incremental data loading strategies
- Data transformation and cleansing
- Threat severity analysis
- Security KPI reporting
- Interactive Power BI dashboards

## Architecture Layers

### Bronze Layer
Raw cybersecurity data is ingested and stored in Azure Data Lake Storage Gen2 without modification.

### Silver Layer
Data is cleaned, standardized, validated, and transformed for analytical processing.

### Gold Layer
Business-ready aggregated datasets are created for reporting and dashboard consumption.

## Key Features

- End-to-end ETL/ELT pipeline architecture
- Incremental processing design
- Scalable cloud-based storage
- Lakehouse implementation using Delta Lake
- Cybersecurity threat analytics
- Reporting and visualization using Power BI
- Enterprise-style project structure

## Reporting & Analytics

Power BI dashboards provide insights into:

- Threat severity distribution
- Failed login attempts
- Suspicious user activity
- Security event trends
- Risk categorization
- Operational KPIs

## Project Goal

The objective of this project is to demonstrate practical cloud data engineering skills by building a production-style cybersecurity analytics platform using Azure services and modern lakehouse architecture principles.
