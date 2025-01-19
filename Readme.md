# BIG DATA ANALYISIS-TASK 1

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** :  ALOK RANJAN SINGH

**INTERN ID** : CT08HAC

**DOMAIN** : Data Analytics

**BATCH DURATION** : December 30th, 2024 to January 30th, 2025.

**MENTOR NAME** : NEELA SANTOSH

---

# ETL Pipeline using PySpark


## Overview

This project demonstrates how to build an ETL (Extract, Transform, Load) pipeline using **PySpark**, a powerful tool for handling large-scale data processing in a distributed environment. The pipeline extracts data from a CSV file, transforms it by cleaning and reshaping the data, and then loads the processed data into a Parquet file for efficient storage and querying.


## Goal

The goal of this project is to create an ETL pipeline that:

- **Extracts** data from a CSV file containing temperature-related information for various countries.
- **Transforms** the data by cleaning missing values, reshaping the temperature data to have 'Year' and 'Temperature' columns, and handling missing country codes.
- **Loads** the processed data into a Parquet file for efficient querying and storage in a distributed system.


## Dataset

The dataset used in this project contains temperature-related data for various countries from 1961 to 2022. It includes columns such as:

- `ObjectId`: Unique identifier for each record
- `Country`: Name of the country
- `ISO2`: 2-letter country code
- `ISO3`: 3-letter country code
- Year-wise temperature data (e.g., `F1961`, `F1962`, etc.)



## Outcome

The outcome of this project is the successful creation of an efficient ETL pipeline that:

- Extracts temperature data from a CSV file.
- Cleans and processes the data, filling missing values and transforming it into a more usable format with a 'Year' and 'Temperature' column.
- Loads the processed data into a csv file for further analysis, ensuring optimized storage and querying.
- The csv file generated from this pipeline is ready for further analysis or can be loaded into any distributed processing environment for additional processing or analysis.

The csv file generated from this pipeline is ready for further analysis or can be loaded into any distributed processing environment for additional processing or analysis.



## Conclusion
This ETL pipeline using PySpark demonstrates how to efficiently handle large datasets, clean and reshape data, and save it in an optimized format for further analysis. PySpark's distributed computing capabilities make it a perfect tool for working with large-scale data processing tasks.


## NOTE
###  **Make sure to have `pyspark` installed.**
