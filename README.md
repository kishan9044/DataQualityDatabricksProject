# DataQuality and Data validation Databricks Project
This is an real time data quality and validation project using Databricks Notebooks

# Project Overview
* This project was carried under the supervision and guidance of Dr. Ricky Sethi (Associate Professor in Computer Science department) during the summer intake, this is an individual project.
* This project was accomplished by using Databricks Community edition provided by AWS.
* The Data quality and validation checks have been accomplished by using an config. JSON document.
* Services used in this project are Microsoft Excel, Azure BLOB storage account, Databricks Community edition and Azure Data Factory.
* Problem Statement – We need to perform the data validation and data quality checks daily by using schedule trigger and we have been provided an config. JSON document file which contains the source path, target path, types of data checks, etc. to be performed making sure that this pipeline can be on 1000 tables of same schema structure with minor changes in notebook parameters.
* During this project created Mount points, Notebook Parameters, made use of provided config. JSON document performed Duplicate Checks, NULL Checks, Negative Checks, Date Format Checks, Datatype Checks on columns, Column name Checks, Data Integrity Checks, Audit table creation.
* Wrote good records to silver layer, rejected records to Rejected layer and audit records to audit layer in the BLOB storage.
* Created two notebook parameters “config_filepath” and “processed_date” which enables the input to be provided while using the Databricks Notebook Activity in pipeline.
