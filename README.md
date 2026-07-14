# Big-Data-Analytics-with-Hadoop-and-Spark

A complete end-to-end Big Data Analytics project demonstrating distributed storage, distributed processing, ETL pipelines, SQL analytics, and interactive business intelligence dashboards using the Hadoop ecosystem.

---

# Project Overview

This project simulates a real-world Big Data pipeline capable of processing large datasets efficiently using Hadoop Distributed File System (HDFS) and Apache Spark.

The workflow includes:

- Data Ingestion
- Distributed Storage (HDFS)
- Data Cleaning
- Data Transformation
- Apache Spark Processing
- Spark SQL Analytics
- KPI Generation
- Power BI Dashboard

---

# Architecture

```

Raw Dataset
│
▼
Python Data Ingestion
│
▼
HDFS Storage
│
▼
Apache Hadoop
│
▼
Apache Spark
│
▼
Spark SQL
│
▼
Data Analytics
│
▼
Power BI Dashboard

```

---

# Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming |
| Hadoop | Distributed Storage Framework |
| HDFS | Distributed File System |
| Apache Spark | Distributed Data Processing |
| Spark SQL | SQL Analytics |
| Pandas | Data Cleaning |
| SQL | Querying |
| Power BI | Dashboard |
| Git | Version Control |

---

# Project Workflow

### Step 1

Load raw data into Python.

### Step 2

Upload datasets into HDFS.

### Step 3

Store data across distributed nodes.

### Step 4

Process data using Apache Spark.

### Step 5

Perform Spark SQL analytics.

### Step 6

Generate KPIs.

### Step 7

Visualize business insights using Power BI.

---

# Hadoop Components Used

- Hadoop Distributed File System (HDFS)
- NameNode
- DataNode
- YARN
- MapReduce
- Hadoop Common

---

# HDFS Operations

- Create Directories
- Upload Files
- Download Files
- Delete Files
- List Files
- View File Contents
- Replication

Example:

```bash
hdfs dfs -mkdir /sales

hdfs dfs -put sales.csv /sales

hdfs dfs -ls /sales

hdfs dfs -cat /sales/sales.csv
```

---

# Spark Operations

- Data Loading
- Filtering
- Aggregation
- Window Functions
- GroupBy
- Joins
- Spark SQL
- Data Export

---

# Analytics Performed

- Revenue Analysis
- Customer Segmentation
- Product Performance
- Regional Sales
- Monthly Trends
- KPI Analysis
- Category Performance

---

# Power BI Dashboard

The dashboard includes

- Revenue KPI
- Sales Trend
- Top Products
- Customer Insights
- Regional Analysis
- Interactive Filters

---

# Repository Structure

```

data/
hadoop/
hdfs/
spark/
sql/
dashboard/
images/
