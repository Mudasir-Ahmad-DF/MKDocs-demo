# Welcome to DecisionFacts

This document serves as a guide for connectors and provides information on their usage and implementation. It is intended to assist users in understanding and utilizing connectors in their desired application. It is created and maintained by our team and serves as a reference for those looking to incorporate connectors into their work.

## DecisionFacts Connectors


## Airtable

```python
from df_connector import airtable

airtable_obj = airtable.connect("Test-airtable-Connector")  # Identifier name which we created in the portal
```

## Analytics

```python
from df_connector import analytics

analytics_obj = analytics.connect("Test-analytics-Connector")  # Identifier name which we created in the portal
```

## Athena

```python
from df_connector.aws import athena

athena_obj = athena.connect("Test-athena-Connector")  # Identifier name which we created in the portal
```
## AWS Logs

```python
from df_connector.aws import logs

aws_logs_obj = logs.connect("Test-logs-Connector")  # Identifier name which we created in the portal
```
## Azure DataLake

```python
from df_connector.azure import datalake

azure_datalake_obj = datalake.connect("Test-datalake-Connector")  # Identifier name which we created in the portal
```
## Azure SQL

```python
from df_connector.azure import sql

azure_sql_obj = sql.connect("Test-sql-Connector")  # Identifier name which we created in the portal
```
## BigQuery

```python
from df_connector.gcp import bigquery

bigquery_obj = bigquery.connect("Test-bigquery-Connector")  # Identifier name which we created in the portal
```
## Cloudwatch

```python
from df_connector.aws import cloudwatch

aws_cloudwatch_obj = cloudwatch.connect("Test-cloudwatch-Connector")  # Identifier name which we created in the portal
```
## Cockroach DB

```python
from df_connector import cockroachdb

cockroachdb_obj = cockroachdb.connect("Test-cockroachdb-Connector")  # Identifier name which we created in the portal
```
## Databricks SQL

```python
from df_connector import databricks

databricks_obj = databricks.connect("Test-databricks-Connector")  # Identifier name which we created in the portal
```
## DataLake

```python
from df_connector.azure import datalake

datalake_service_client = datalake.connect_service_client("Test-datalake-Connector")  # Identifier name which we created in the portal

datalake_file_system_client = datalake.connect_file_system_client("Test-datalake-Connector","<File_system_name>")  # provide which container need an access

datalake_directory_client = datalake.connect_directory_client("Test-datalake-Connector","<file_system_name>","<directory_name")  # provide container and directory name which need an access

datalake_file_client = datalake.connect_file_client("Test-datalake-Connector","<file_system_name>","<directory_name","<file_path>")  # provide container,directory and file name which need an access

datalake_table_service_client = datalake.connect_table_service_client("Test-datalake-Connector")  # Identifier name which we created in the portal

datalake_table_client = datalake.connect_table_client("Test-datalake-Connector","<table_name>")  # provide table name which need an access


```
## DynamoDB

```python
from df_connector.dynamodb import dynamodb

aws_dynamodb_obj = dynamodb.connect("Test-dynamodb-Connector")  # Identifier name which we created in the portal
```
## Facebook

```python
from df_connector.meta import facebook

meta_facebook_obj = facebook.connect("Test-facebook-Connector")  # Identifier name which we created in the portal
```
## Fedex

```python
from df_connector import fedex

fedex_obj = fedex.connect("Test-fedex-Connector")  # Identifier name which we created in the portal
```
## GCP Storage

```python
from df_connector.gcp import storage

storage_obj = storage.connect("Test-storage-Connector")  # Identifier name which we created in the portal
```
## Google Sheets

```python
from df_connector.gcp import sheets

sheets_obj = sheets.connect("Test-sheets-Connector")  # Identifier name which we created in the portal
```
## Jira

```python
from df_connector import jira

jira_obj = jira.connect("Test-jira-Connector")  # Identifier name which we created in the portal
```
## Mongo

```python
from df_connector import mongo

mongo_obj = mongo.connect("Test-Mongo-Connector")  # Identifier name which we created in the portal
```
## MSSQL

```python
from df_connector import mssql

mssql_obj = mssql.connect("Test-mssql-Connector")  # Identifier name which we created in the portal
```

## MySQL

```python
from df_connector import mysql

mysql_obj = mysql.connect("Test-mysql-Connector")  # Identifier name which we created in the portal
```
## Oracle DB

```python
from df_connector import oracle

oracle_obj = oracle.connect("Test-oracle-Connector")  # Identifier name which we created in the portal
```
## PostgreSQL

```python
from df_connector import postgresql

postgresql_obj = postgresql.connect("Test-postgresql-Connector")  # Identifier name which we created in the portal
```
## Redshift

```python
from df_connector.aws import redshift

aws_redshift_obj = redshift.connect("Test-Redshift-Connector")  # Identifier name which we created in the portal
```
## Run Metrics

```python
from df_connector.system import metrics

content = metrics.run.get_csv("<start_date>", "<end-date>")
```
## Run Metrics Paramters

```python
from df_connector.system import metrics

content = metrics.tracking.get_params("<start_date>", "<end-date>")
```
## Run Metrics Tracking

```python
from df_connector.system import metrics

content = metrics.tracking.get_csv("<start_date>", "<end-date>")
```
## S3

```python
from df_connector.aws import s3

aws_s3_obj = s3.connect("Test-S3-Connector")  # Identifier name which we created in the portal
```
## Salesforce

```python
from df_connector import salesforce

salesforce_obj = salesforce.connect("Test-salesforce-Connector")  # Identifier name which we created in the portal
```
## SAP HANA

```python
from df_connector import sap_hana

sap_conn = sap_hana.connect("Test_connector") # Identifier name which we created in the portal
```
## SFTP

```python
from df_connector import sftp

sftp_obj = sftp.connect("Test-sftp-Connector")  # Identifier name which we created in the portal
```
## Shopify

```python
from df_connector import shopify

shopify_obj = shopify.connect("Test-shopify-Connector")  # Identifier name which we created in the portal
```
## Snowflake

```python
from df_connector import snowflake

snowflake_obj = snowflake.connect("Test-Snowflake-Connector")  # Identifier name which we created in the portal
```

































## UPS

```python
from df_connector import ups

ups_obj = ups.connect("Test-ups-Connector")  # Identifier name which we created in the portal
```







## Vertica Analytics

```python
from df_connector import vertica

vertica_obj = vertica.connect("Test-vertica-Connector")  # Identifier name which we created in the portal

```

