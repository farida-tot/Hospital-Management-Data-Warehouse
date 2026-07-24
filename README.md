# Hospital Management Data Warehouse & ETL Pipeline

A SQL Server Integration Services (SSIS) project that builds a healthcare data warehouse by extracting, transforming, and loading data from multiple heterogeneous sources. The project integrates hospital operational data into a unified dimensional model for reporting and business intelligence.

---

## Features

- ETL pipeline developed using SQL Server Integration Services (SSIS)
- Data extraction from XML, CSV, and API sources
- Data cleansing and transformation
- Schema integration and data unification
- Incremental loading
- Slowly Changing Dimension (SCD Type 6)
- Historical data versioning
- Analytical data preparation for reporting

---

## Technologies Used

- SQL Server
- SQL Server Integration Services (SSIS)
- SQL Server Management Studio (SSMS)
- Data Warehouse
- ETL
- XML
- CSV
- REST API

---

## Data Warehouse Design

The project follows a dimensional modeling approach consisting of:

### Dimension Tables

- Patient
- Doctor
- Nurse
- Room
- Department
- Date
- Time
- Other supporting dimensions

### Fact Tables

- Appointments
- Visits
- Surgeries

---

## ETL Workflow

The ETL process includes:

1. Extract data from multiple heterogeneous sources.
2. Clean and validate incoming data.
3. Transform and standardize schemas.
4. Load dimension tables.
5. Apply Slowly Changing Dimension (SCD Type 6).
6. Load fact tables.
7. Generate integrated datasets for reporting.

---

## Project Structure

```
Hospital Management DW
│
├── Dimension Packages
├── Fact Packages
├── Master ETL Package
├── SQL Scripts
└── Documentation
```

---

## Learning Outcomes

This project demonstrates practical experience with:

- Data Warehouse Design
- ETL Development
- SSIS Package Development
- Incremental Loading
- Slowly Changing Dimensions (SCD Type 6)
- Data Integration
- Business Intelligence Fundamentals

---

## Future Improvements

- Interactive Power BI Dashboard
- Data Quality Validation Reports
- ETL Logging and Error Handling
- Automated Scheduling using SQL Server Agent

---

## Author

**Farida Ahmed**

Faculty of Computer Science & Artificial Intelligence

Cairo University
