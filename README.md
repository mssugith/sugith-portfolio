# sugith-portfolio

**About Me: **
I'm a Data Engineer with 5+ years of experience, including 4+ years building production-grade data platforms on Google Cloud Platform. I specialize in batch and event-driven pipelines using BigQuery, Cloud Composer (Airflow), Dataflow, Dataproc, Cloud Run, Pub/Sub and Eventarc. I've implemented Medallion Architecture (Bronze/Silver/Gold) lakehouses with BigLake and Apache Iceberg, and migrated legacy Hadoop/Hive workloads to GCP-native services. I care about reliable, cost-efficient pipelines, with results like 40% faster queries, 25% lower storage costs and 60% less manual oversight. I hold a Master's in Data Science and Analytics from the University of Hertfordshire, UK.

**Skills:**
Cloud Computing Platforms: BigQuery, BigLake, Cloud Composer (Apache Airflow), Cloud Dataflow, Dataproc, Cloud
Run (Jobs & Services), Cloud Functions, Cloud Storage (GCS), Cloud SQL, Pub/Sub, Eventarc, Cloud Build, GKE, Cloud
Logging & Monitoring, Cloud Shell SDK, IAM
Programming Languages: Python (primary), SQL, PySpark, Scala, Shell/Linux Commands
Python Libraries & Frameworks: Pandas, NumPy, PySpark, google-cloud-bigquery, google-cloud-storage,
google-cloud-pubsub, Apache Beam (Dataflow), Requests (REST API integration), Matplotlib
ETL & Orchestration: Apache Airflow / Cloud Composer (custom DAGs, operators, sensors), Cloud Dataflow,
event-driven and batch pipelines, incremental loads and historical backfills, Medallion Architecture (Bronze/Silver/Gold)
Big Data Technologies: Apache Spark, Spark SQL, PySpark, Apache Kafka, Hadoop, HDFS, Hive, Sqoop, YARN
Data Warehousing & Storage Formats: BigQuery, Apache Iceberg, Parquet, NDJSON, Avro, partitioned data lakes
Databases: BigQuery, Cloud SQL, PostgreSQL, SQL Server, MySQL
AWS (secondary): S3, Glue, EMR, Athena, CloudWatch, RDS
DevOps & Version Control: Git, GitHub, Gitflow, Docker, Cloud Build, CI/CD pipelines
Methodologies: Agile/Scrum, JIRA, data modeling (star schema, dimensional), data quality validation, data lineage &
governance, performance tuning, cost optimization

**Experience Summary**
Role	Company	Duration
Data Engineer (Client: HCA)	Egen	Aug 2025 – Present
Data Engineer	Acciva Technosoft	Apr 2023 – Jun 2025
Engineer	Thirdbridge	Aug 2022 – Mar 2023
Egen: Building config-driven Airflow ingestion frameworks, event-driven Medallion pipelines (GCS → Eventarc → Cloud Run) and Iceberg tables in BigQuery.
Acciva Technosoft: Built Dataflow/Dataproc pipelines on TB-scale data, migrated Hadoop/Hive to GCP, and cut query runtime by 40%.
Thirdbridge: Delivered Airflow ETL into BigQuery and real-time streaming with Kafka, Pub/Sub and Dataflow.

**Featured Projects**
**1. Config-Driven REST API Ingestion Framework**
Parameter-driven pipeline that pulls data from a third-party REST API into BigQuery, supporting historical backfills and incremental runs. Airflow triggers Cloud Run Jobs that stage NDJSON files in GCS, then load them into per-site landing tables. One DAG template scales to many locations with no code duplication. Tech: Python · Cloud Composer (Airflow) · Cloud Run Jobs · GCS · BigQuery 🔗 Repository
**2. Event-Driven Medallion Lakehouse on GCP**
Real-time file ingestion where GCS notifications fire Eventarc, triggering Cloud Run services that decrypt PGP files and stage them in the Bronze layer. Data is cleaned in Silver and curated into Gold as Apache Iceberg tables in BigQuery. Tech: GCS · Eventarc · Cloud Run · Python · BigQuery · Apache Iceberg 🔗 Repository
**3. Hadoop/Hive to GCP Migration with PySpark**
Migration of legacy Hive workflows to Dataproc and GCS (Parquet), tuned with partitioning, predicate pushdown, caching and broadcast joins. Achieved 40% faster queries, 25% lower storage costs and 30% higher throughput. Tech: PySpark · Spark SQL · Dataproc · GCS · Parquet · BigQuery 🔗 Repository
**4. Real-Time Streaming Pipeline**
Streaming architecture processing bounded and unbounded data, using Kafka and Pub/Sub as sources and Dataflow (Apache Beam) for transformations, with results written to BigQuery for near-real-time analytics. Tech: Apache Kafka · Pub/Sub · Dataflow (Apache Beam) · Cloud Functions · BigQuery 🔗 Repository
**5. BigQuery Analytics & Looker Studio Dashboards**
Partitioned BigLake/BigQuery data lake with optimized SQL (CTEs, window functions) that reduced report generation from hours to minutes, plus self-service dashboards in Looker Studio. Tech: BigQuery · BigLake · SQL · Looker Studio 🔗 Repository

**Certifications**
Google Cloud Certified - Professional Data Engineer | Google
Issued Apr 2026 - Expires Apr 2028 | Credential ID: d31f9fff-6d89-4f14-8651-a55bff0762b5
Google Cloud Certified - Associate Data Practitioner | Google
Issued Feb 2026 - Expires Feb 2029 | Credential ID: d464f09c-eb38-4fc2-9c3b-d39277eac9ad
