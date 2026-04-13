# Data Warehouse Project – CRM & ERP Integration

## Overview

This project implements a **Data Warehouse** designed to organize and prepare data for analytical purposes. The primary objective is to ingest raw data from multiple source systems — specifically **CRM** and **ERP** platforms, provided as CSV files — then clean, transform, and structure the data to ensure accuracy and readiness for analysis.

The final output enables data‑driven decision‑making by providing reliable, ready‑to‑use datasets for reporting and business intelligence.

## Architecture

The data warehouse follows a **three‑layer architecture**:

### 1. Bronze Layer (Raw Data)
- Stores data exactly as extracted from source systems.
- No transformations or cleaning are applied at this stage.
- Preserves the original state for auditability and reprocessing.

### 2. Silver Layer (Cleaned & Transformed Data)
- Applies data cleaning and transformation logic.
- Handles errors, inconsistencies, missing values, and data quality issues.
- Produces consistent, reliable, and validated datasets.

### 3. Gold Layer (Aggregated & Analytical Data)
- Organizes data into business‑ready structures (e.g., dimension and fact tables).
- Performs aggregations, joins, and business logic calculations.
- Optimised for reporting, dashboards, and advanced analytics.

## Purpose

This project demonstrates a practical, end‑to‑end data warehouse pipeline — from raw CSV extracts to analysis‑ready information — following industry best practices for data engineering and ETL/ELT processes.
