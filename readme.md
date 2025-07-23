Big Data Log Analyzer


* Purpose : collect web server logs-> analyzing-> dashboard visualization
* (Skill Stack: Python, Scala, Spark
* Store: HDFS, AWS S3 or GCP Storage

* Flow Summary
1. create or collect logs from web
2. store raw logs(HDFS, S3 or GCP storage)
3. analyzing logs through Spark(batch jobs)
4. save results(csv/json/parquet)
5. scheduling using Airflow
6. Visualizing results(Superset/Grafana/ELK)

* Environment Setup
- install Spark
- install and set up Scala + SBT
- Hadoop, S3 or GCP Storage
- Airflow
- Superset or ELK


