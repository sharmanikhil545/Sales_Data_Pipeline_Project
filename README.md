# Google Cloud Data Analytics Project
This repository contains code and configuration files for Google Cloud Data Analytics Project.This project demonstrates the integration of several GCP services to create an efficient and automated data pipeline for sales data. We'll show you how to:


![image](https://github.com/user-attachments/assets/bce32e82-66b9-4f30-96c5-7bcfad768ac0)

## Overview

1. **Web Portal**: Built with Python Flask to allow users to upload sales data files.
2. **Storage**: Uploaded files are stored in a GCS bucket.
3. **Cloud Function**: Automatically triggered when a file is uploaded to the GCS bucket, extracts data from the file, and loads it into BigQuery.
4. **ETL Process**: Extract, Transform, Load process implemented to handle data from raw upload to processed state.
5. **Reporting**: Summary views and dashboards in Looker Studio for key metrics, with filtering and drill-down capabilities.

![image](https://github.com/user-attachments/assets/4a04d798-ccc7-4236-a883-701500adc0d3)


## Architecture
![image](https://github.com/user-attachments/assets/6a1fbbda-d0ee-4666-9e2d-4bff40796645)

## Dashboard


<img width="854" alt="Screenshot 2024-09-18 at 2 53 17 AM" src="https://github.com/user-attachments/assets/faa16a8f-88eb-4a86-aecc-0079f5f8ee50">
<img width="854" alt="Screenshot 2024-09-18 at 2 58 04 AM" src="https://github.com/user-attachments/assets/e82e1bc4-61f6-4a10-9805-2b72d576d136">




