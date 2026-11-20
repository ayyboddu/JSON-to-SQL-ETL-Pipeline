# Event-Stream JSON-to-SQL ETL Pipeline

## Overview
Engineered an automated Python data ingestion and schema transformation pipeline that parses nested, semi-structured JSON payloads from the GitHub Events API and normalizes them into structured relational SQL tables and graph-ready entity relationships.

## Architecture & Technical Implementation
- **Semi-Structured Data Ingestion:** Extracted and flattened nested JSON event logs in Python, handling schema variability, null imputation, and timestamp standardization.
- **Relational Schema Normalization:** Designed normalized relational table structures (3NF) with primary/foreign key constraints to eliminate data redundancy and support efficient multi-table joins.
- **Graph & Analytical Readiness:** Structured entity-relationship mappings (actors, repositories, event types, and temporal logs) to enable downstream SQL analytical queries and network/graph traversal.

## Tech Stack
`Python` · `SQL` · `JSON / REST APIs` · `Relational Data Modeling` · `ETL Pipelines`
