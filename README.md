# Nilesh Thorat — GitHub Profile README

# Hi, I'm Nilesh Thorat 👋

### 🚀 Data Engineer | Python • SQL • PySpark • Kafka • Databricks • Azure • GCP • Fabric • Agentic AI

I am a **Data Engineer with 4+ years of experience** designing and developing scalable batch, streaming, and cloud data platforms.

My work focuses on **data pipeline engineering, distributed processing, Lakehouse architecture, real-time analytics, workflow orchestration, data quality, performance optimization, and AI-assisted data engineering**.

I enjoy building systems that go beyond simple ETL — including **streaming architectures, medallion pipelines, monitoring and alerting frameworks, automated data-quality controls, CI/CD pipelines, and AI-powered engineering assistants**.

* 📍 **Location:** Pune, India
* 💼 **Role:** Data Engineer
* 🎓 **Education:** B.Tech, KIT College of Engineering, Kolhapur
* 🔗 **LinkedIn:** [linkedin.com/in/nilesh0208](https://linkedin.com/in/nilesh0208)
* 📧 **Email:** [nilesh.thorat297@gmail.com](mailto:nilesh.thorat297@gmail.com)

---

## 🛠️ Technical Stack

### Languages & Data Processing

`Python` • `SQL` • `PySpark` • `Pandas` • `Shell Scripting` • `Apache Spark` • `Spark Structured Streaming`

### Streaming & Distributed Systems

`Apache Kafka` • `Spark Structured Streaming` • `Event-Driven Processing` • `Checkpointing` • `Schema Evolution`

### Cloud & Data Platforms

**Azure:**
`Azure Data Factory` • `ADLS Gen2` • `Azure Databricks` • `Azure Synapse Analytics` • `Azure SQL Database` • `Azure Key Vault` • `Azure Monitor`

**Google Cloud Platform:**
`BigQuery` • `Google Cloud Storage` • `Dataproc` • `Cloud Composer` • `Pub/Sub`

**Microsoft Fabric:**
`Lakehouse` • `Data Engineering` • `Data Pipelines`

**Additional Cloud Exposure:**
`AWS S3` • `Redshift` • `AWS Glue`

### Data Engineering & Modeling

`ETL / ELT` • `Medallion Architecture` • `Bronze / Silver / Gold` • `Delta Lake` • `Incremental Processing` • `CDC Concepts` • `Dimensional Modeling` • `Data Warehousing`

### Orchestration & Transformation

`Apache Airflow` • `Cloud Composer` • `Azure Data Factory` • `dbt`

### Databases & Analytics

`PostgreSQL` • `BigQuery` • `Azure SQL Database` • `Power BI` • `Grafana`

### Data Quality, Testing & DevOps

`Data Validation` • `Schema Enforcement` • `Rejected-Record Quarantine` • `pytest` • `Docker` • `Docker Compose` • `Git` • `GitHub Actions` • `CI/CD`

### AI-Assisted Data Engineering

`Gemini API` • `FastAPI` • `Function Calling` • `Agentic Workflows` • `SQL Generation` • `Pipeline Planning` • `Deterministic Validation`

---

## 🏆 Certifications

* 📜 **Microsoft Certified: Fabric Data Engineer Associate — 2026**
* 📜 **Databricks Certified Data Engineer Professional — 2025**
* 📜 **Google Cloud Professional Data Engineer — 2025**

---

# 🚀 Featured Projects

## 📈 Real-Time Stock Market Analytics Platform

### [View Repository →](https://github.com/Nilesh0208/stock-market-data-pipeline)

**Tech Stack:**
`Python` • `Apache Kafka` • `Spark Structured Streaming` • `PostgreSQL` • `Docker` • `Airflow` • `Grafana` • `Power BI` • `pytest` • `GitHub Actions`

An end-to-end streaming Data Engineering platform designed to process stock-market events in near real time.

### Architecture

```text
Python Producer
      ↓
Apache Kafka
      ↓
Spark Structured Streaming
      ↓
Bronze Layer
      ↓
Silver Layer
      ↓
Gold Layer
      ↓
PostgreSQL
      ↓
Power BI / Grafana
```

### Key Engineering Features

* Built a fully containerized streaming architecture using **Docker Compose**.
* Implemented **Kafka-based event ingestion** and Spark Structured Streaming processing.
* Designed **Bronze, Silver, and Gold Medallion architecture**.
* Added schema validation and rejected-record quarantine.
* Implemented checkpointing and fault-tolerant streaming.
* Designed idempotent batch processing to prevent duplicate Gold-layer writes.
* Added batch-level operational auditing.
* Implemented configurable data-quality thresholds.
* Created pipeline health states including **HEALTHY, WARNING, and CRITICAL**.
* Built operational alert lifecycle handling for:

  * OPEN
  * ACKNOWLEDGED
  * RESOLVED
* Added PostgreSQL monitoring views for operational observability.
* Integrated **Grafana dashboards** for pipeline monitoring.
* Built **Power BI analytics dashboards** for stock metrics.
* Added Airflow-based monitoring capabilities.
* Implemented automated tests using `pytest`.
* Added GitHub Actions CI validation.
* Documented architecture, setup, monitoring, troubleshooting, and pipeline flows.

### Analytics Generated

The Gold layer calculates metrics including:

* 1-minute stock aggregates
* Average trading price
* Total volume
* Processing latency
* Operational pipeline health
* Valid/rejected record statistics

---

## 🤖 AI Data Pipeline Copilot

### [View Repository →](https://github.com/Nilesh0208/ai-data-pipeline-copilot)

**Tech Stack:**
`Python` • `FastAPI` • `Gemini` • `PostgreSQL` • `Docker` • `pytest` • `SQL`

An AI-assisted Data Engineering system designed to convert natural-language pipeline requirements into structured engineering outputs while keeping critical validation deterministic.

### Core Capabilities

* Natural-language Data Engineering requirement interpretation.
* AI-generated SQL with controlled execution boundaries.
* Gemini function-calling integration.
* Structured pipeline-plan generation.
* Data-quality rule generation.
* Incremental-load planning.
* SQL safety and validation guardrails.
* Deterministic validation after AI generation.
* PostgreSQL metadata integration.
* FastAPI-based service layer.
* Automated test coverage using `pytest`.
* Dockerized local development environment.

### Engineering Philosophy

The project intentionally separates:

```text
AI Reasoning
     +
Deterministic Engineering Validation
```

The AI proposes pipeline artifacts while application-side validation ensures generated outputs follow predefined Data Engineering rules and safety constraints.

This project explores how **Agentic AI can augment Data Engineering workflows without giving unrestricted control to the model**.

---

## 🧠 Data Engineering Problems

### [View Repository →](https://github.com/Nilesh0208/data-engineering-problems)

A long-term problem-solving repository focused on strengthening practical Data Engineering fundamentals through **Python and SQL**.

Rather than focusing on basic programming exercises, the repository emphasizes Data Engineering-oriented scenarios.

### Areas Covered

**Python**

* Data processing
* Data validation
* Transformation logic
* Deduplication
* Record cleaning
* Pipeline-style coding problems
* Interview scenarios

**SQL**

* Analytical SQL
* Window functions
* Ranking problems
* Aggregations
* Joins
* CTEs
* Data-quality queries
* Data Engineering interview problems

The repository is continuously expanded to demonstrate **consistent engineering practice and problem-solving discipline**.

---

## 🗄️ SQL Database Loader

### [View Repository →](https://github.com/Nilesh0208/SQL-database-Loader)

A Python-based Data Engineering utility focused on loading structured datasets into SQL databases.

The project demonstrates practical pipeline concepts such as:

* File ingestion
* Data validation
* Database connectivity
* Transformation
* SQL loading
* Error handling
* Modular pipeline design

It complements my larger distributed-processing projects by demonstrating the fundamentals of building reliable ingestion utilities.

---

# 🏗️ Engineering Areas I Focus On

My projects and professional learning currently focus on:

* Scalable batch data pipelines
* Real-time and near-real-time streaming
* Distributed data processing
* Lakehouse architecture
* Medallion architecture
* Incremental data processing
* Data-quality frameworks
* Pipeline observability
* Workflow orchestration
* Fault tolerance and retry handling
* Idempotent processing
* SQL performance optimization
* Cloud Data Engineering
* CI/CD for data platforms
* AI-assisted Data Engineering workflows

---

# 📊 Selected Engineering Achievements

### ⏱️ Reporting Latency

Reduced reporting and data-delivery latency from hours to **under 5 minutes** using Kafka and Spark-based processing.

### ⚡ BigQuery Performance

Reduced query runtime from approximately **12 minutes to under 4 minutes** through:

* Partitioning
* Clustering
* Query refactoring
* Efficient data filtering

### 💰 Cloud Cost Optimization

Reduced cloud infrastructure spend by approximately **25%** through resource right-sizing and workload optimization.

### 🗄️ Lakehouse Storage Optimization

Reduced Delta Lake storage overhead by approximately **30%** using:

* Compaction strategies
* Optimized MERGE operations
* Efficient incremental processing

---

# 🧩 Data Engineering Architecture Experience

I am particularly interested in building systems around patterns such as:

```text
Sources
   ↓
Ingestion
   ↓
Raw / Bronze Layer
   ↓
Validation & Transformation
   ↓
Silver Layer
   ↓
Business Aggregations
   ↓
Gold Layer
   ↓
Warehouse / Serving Layer
   ↓
Analytics / BI / APIs
```

with supporting capabilities for:

```text
Orchestration
Monitoring
Data Quality
Alerting
Testing
CI/CD
Security
Cost Optimization
```

---

# 🎯 Current Focus

I am continuing to deepen my knowledge in:

* Advanced Data Engineering architecture
* Azure Data Services
* Apache Spark optimization
* Databricks and Delta Lake
* Kafka and streaming systems
* Advanced SQL
* Data platform reliability
* Cloud-native Data Engineering
* Data observability
* Agentic AI for Data Engineering
* Production-grade AI-assisted pipeline automation

---

# 📫 Connect With Me

I'm always interested in discussions around **Data Engineering, distributed systems, cloud data platforms, streaming architectures, and AI-assisted engineering**.

<p align="left">

<a href="https://linkedin.com/in/nilesh0208" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="mailto:nilesh.thorat297@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</p>

---

### 💡 Building reliable data platforms one pipeline at a time.
