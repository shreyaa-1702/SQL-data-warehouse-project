# SQL-data-warehouse-project
Building a modern SQL data warehouse with SQL server, including ETL, data modeling and analytics.

Data Warehouse and Analytics Project
Welcome to the Data Warehouse and Analytics Project repository! 🚀
# Data Warehouse & Analytics Project

A comprehensive end-to-end data warehousing and analytics solution built using SQL Server, following the **Medallion Architecture** (Bronze → Silver → Gold). This project demonstrates industry best practices in data engineering, ETL pipeline development, data modeling, and business intelligence reporting.

---

## 📐 Data Architecture

This project is structured around the **Medallion Architecture**, comprising three progressive layers:

| Layer | Description |
|-------|-------------|
| **Bronze** | Raw data ingested as-is from source CSV files into SQL Server |
| **Silver** | Cleansed, standardized, and normalized data prepared for analysis |
| **Gold** | Business-ready data modeled into a star schema for reporting and analytics |

---

## 📖 Project Overview

This project covers the full lifecycle of a modern data warehouse, including:

- **Data Architecture** — Designing a scalable warehouse using the Medallion Architecture pattern
- **ETL Pipelines** — Extracting, transforming, and loading data from source systems into the warehouse
- **Data Modeling** — Building fact and dimension tables optimized for analytical queries
- **Analytics & Reporting** — Developing SQL-based reports for actionable business insights

---

## 🚀 Project Requirements

### 🏗️ Data Engineering — Building the Data Warehouse

**Objective:**
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications:**
- **Data Sources:** Import data from two source systems — ERP and CRM — provided as CSV files
- **Data Quality:** Identify and resolve data quality issues prior to analysis
- **Integration:** Merge both sources into a unified, query-optimized data model
- **Scope:** Focus on the latest dataset only; historical data versioning is not required
- **Documentation:** Provide clear data model documentation for both business and technical stakeholders

---

### 📊 BI & Analytics — Reporting Layer

**Objective:**
Develop SQL-based analytics to generate detailed insights across three key areas:

- **Customer Behavior** — Understand purchasing patterns and customer segmentation
- **Product Performance** — Identify top-performing and underperforming products
- **Sales Trends** — Track revenue and growth over time

These insights enable stakeholders to make data-driven strategic decisions.

> For detailed specifications, refer to [`docs/requirements.md`](docs/requirements.md)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **SQL Server Express** | Lightweight database server for hosting the data warehouse |
| **SQL Server Management Studio (SSMS)** | GUI for database management and query execution |
| **CSV Datasets** | Source data representing ERP and CRM systems |
| **Draw.io** | Designing architecture diagrams, data flows, and data models |
| **Git & GitHub** | Version control and project collaboration |
| **Notion** | Project management and task tracking |

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                        # Raw source datasets (ERP and CRM CSV files)
│
├── docs/                            # Project documentation and architecture diagrams
│   ├── data_architecture.drawio     # Overall data architecture diagram
│   ├── data_flow.drawio             # Data flow across all layers
│   ├── data_models.drawio           # Star schema and data model diagrams
│   ├── etl.drawio                   # ETL techniques and methods overview
│   ├── data_catalog.md              # Dataset field descriptions and metadata
│   └── naming-conventions.md       # Naming standards for tables, columns, and files
│
├── scripts/                         # SQL scripts for ETL and transformations
│   ├── bronze/                      # Scripts for raw data extraction and loading
│   ├── silver/                      # Scripts for data cleansing and transformation
│   └── gold/                        # Scripts for analytical model creation
│
├── tests/                           # Data quality and validation test scripts
│
├── README.md                        # Project overview and setup instructions
├── LICENSE                          # License information
├── .gitignore                       # Files and directories excluded from version control
└── requirements.txt                 # Project dependencies and requirements
```

---

## 🏁 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/shreyaa-1702/data-warehouse-project.git
   ```

2. **Set up SQL Server Express** and create a new database instance

3. **Load the datasets** from the `/datasets` folder into the Bronze layer using the provided scripts

4. **Run scripts in order:** Bronze → Silver → Gold

5. **Explore the analytics queries** in the `/scripts/gold` folder for reporting insights

---

## 📄 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

---

## 🙋 Contributing

Contributions, suggestions, and feedback are welcome. Please open an issue or submit a pull request for any improvements.

Let's stay in touch! Feel free to connect with me on the following platforms:
