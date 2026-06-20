# ecommerce-etl-data-warehouse
ETL Data Warehouse Project using PostgreSQL, Stored Procedure, Partitioning, and Data Mart

## Overview

This project demonstrates an end-to-end ETL process using PostgreSQL.

The project includes:

- Staging Layer
- Dimension Tables
- Fact Table
- Data Mart
- Stored Procedure Automation
- Table Partitioning

---

## Architecture

Source Data
↓
Staging
↓
Dimension Tables
↓
Fact Table
↓
View
↓
Cube
↓
Data Mart

---

## Data Marts

### Transaction User Hour

- Total transactions per hour
- Total users per hour

### Quantity Product

- Top selling products

### Quantity Store

- Top performing stores

### Product Category Revenue

- Revenue by product category

---

## Technologies

- PostgreSQL
- SQL
- Data Warehouse
- ETL
- Stored Procedure
- Partitioning

---

## Run Procedure

```sql
CALL dwh.generate_ecommerce_transaction();
```
