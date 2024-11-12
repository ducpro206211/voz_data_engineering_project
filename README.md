# voz_data_engineering_project
# Project Overview

The goal of this project is to understand and set up basic components for both batch and real-time data engineering solutions.

<img src="https://static.wikia.nocookie.net/gensin-impact/images/0/05/Icon_Emoji_Paimon%27s_Paintings_18_Cyno_3.png/revision/latest?cb=20221020052700" alt="Cyno Emoji" width="100">

---

## Problem Definition

The project involves the following tasks:
1. **Data Crawling:** Extract data from the *voz* forum.  
2. **Workflow Orchestration:** Use Apache Airflow to manage workflows in a simple manner.  
3. **Data Validation:** Perform data validation with exception handling before inserting data into PostgreSQL.  
4. **Change Data Capture (CDC):** Use Debezium to capture changes in PostgreSQL and send logs to Kafka.  
5. **Stream Processing:** Use Spark Streaming to transform data and load it into Apache Doris as a data warehouse.  
6. **Visualization:** Connect Apache Doris to Superset for building and visualizing dashboards.

---

## Requirements

- The system should operate smoothly and reliably.
- It must be packaged in a **YAML file** to enable easy deployment using Docker.
