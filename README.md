# Airline-Data-Ingestion
➢	Ingest daily flight data in Redshift fact table     
   Tech Stack – S3, Glue Crawler, Glue Visual ETL, Event Bridge Pattern rule, SNS, Redshift, Step Function.

●	Automated daily ingestion of flight data from S3 upstream to Redshift fact table.
●	Schema discovery from raw data in S3 was achieved by utilizing Glue crawlers.
●	Glue ETL job enabled the seamless data transformation from raw files stored in Amazon S3 to a structured format suitable for analytics in Redshift.
●	Orchestrated the entire data pipeline using Step Functions, ensuring seamless coordination and execution of each processing step
●	Notifications were configured to trigger alerts for pipeline failures or anomalies, enabling prompt identification and resolution of issues.
