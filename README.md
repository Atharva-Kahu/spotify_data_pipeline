Spotify Data Pipeline

A complete end-to-end Spotify Data Pipeline leveraging Apache Airflow, AWS S3, AWS Glue, Amazon Redshift, and Tableau for data extraction, transformation, loading, and visualization.

📊 Project Overview
This project builds a robust data pipeline that extracts data from the Spotify API, processes it, and stores it in a Redshift data warehouse for analytics and visualization using Tableau.

⚙️ Technologies Used
Apache Airflow – Orchestration of ETL processes
Spotify API – Data extraction for tracks, albums, and artists
AWS S3 – Data storage (raw and processed data)
AWS Glue – Data transformation and schema management
Amazon Redshift – Data warehousing
Tableau – Data visualization
Python – Core programming language

🛠️ Features
✅ Automated data extraction from Spotify API using Airflow
✅ Store raw data in AWS S3 buckets
✅ Data transformation using AWS Glue
✅ Load transformed data into Amazon Redshift
✅ Data visualization in Tableau

🚀 How It Works
Extract – Airflow triggers a DAG to pull data from Spotify API.
Load Raw Data – Raw data is saved in AWS S3.
Transform – AWS Glue processes and cleans data.
Load to Redshift – Transformed data is moved to Amazon Redshift.
Visualize – Tableau connects to Redshift for data analysis.

📊 Tableau Dashboard
Connect Tableau to Amazon Redshift.
Build dashboards to analyze Spotify track trends, artist popularity, and more.

✅ Future Improvements
Implement advanced scheduling and monitoring in Airflow.

