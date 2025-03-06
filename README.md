# ETL Project with Data Fusion, Airflow, and BigQuery

## Description
This repository contains code and configuration files for an Extract, Transform, Load (ETL) project using Google Cloud Data Fusion for data extraction, Apache Airflow/Composer for orchestration, and Google BigQuery for data loading.

## Overview
The project aims to perform the following tasks:

Data Extraction: Extract data using python.
Data Masking: Apply data masking & encoding techniques to sensitive information in Cloud Data Fusion before loading it into BigQuery.
Data Loading: Load transformed data into Google BigQuery tables.
Orchestration: Automate complete Data pipeline using Airflow ( Cloud Composer )

## Features
- Predicts insurance charges based on BMI, number of children, smoking status, age category, and gender.
- Serverless API accessible via HTTP POST requests.
  
## Technologies
- Python (Pandas, Scikit-learn, NumPy), GCP (Cloud Run/Functions, Cloud Storage), Functions Framework.

## Installation 
- Clone this repository, install dependencies with **pip install -r requirements.txt**, and deploy using GCP CLI or Console.

## Usage
- Test the API with **python test.py** after updating the URL.

## Deployment Instructions
- Deploy manually in GCP Cloud Run (or Functions if available) with the inline editor or CLI: **gcloud run deploy predict-insurance-manual --region us-central1 --allow-unauthenticated --source**

## Image Preview
![Students Admission Report](https://github.com/muhdshahan/PJ5-Students-Admission-Report/blob/main/Students%20Admission%20Report.png)

## Contact
For questions, contact me at **shahuuraff@gmail.com** or connect on LinkedIn.
