# x(Twitter)-airflow-data-engineering-project
This project demonstrates an end-to-end Data Engineering Pipeline built using Python, Apache Airflow, and the X (Twitter) API.

The pipeline automatically extracts data from X, performs data transformation and cleaning, and stores the processed dataset for further analytics and reporting.

The primary goal of this project is to understand:

Data Extraction
ETL (Extract, Transform, Load)
Workflow Orchestration
Task Scheduling
Pipeline Monitoring


Automation using Apache Airflow
 Architecture
┌───────────────┐
│  X API        │
└──────┬────────┘
       │
       ▼
┌───────────────┐
│ Python ETL    │
│ Extraction    │
└──────┬────────┘
       │
       ▼
┌───────────────┐
│ Data Cleaning │
│ Transformation│
└──────┬────────┘
       │
       ▼
┌───────────────┐
│ Apache Airflow│
│ DAG Scheduler │
└──────┬────────┘
       │
       ▼
┌───────────────┐
│ Output File   │
│ CSV / Storage │
└───────────────┘

Apache Airflow is used to orchestrate the entire workflow through DAGs (Directed Acyclic Graphs), allowing automatic scheduling and monitoring of ETL jobs
