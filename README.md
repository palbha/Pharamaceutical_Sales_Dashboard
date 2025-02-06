# Sales Dashboard Analysis and Transformation

![Sales Dashboard](https://github.com/user-attachments/assets/25764fb1-971a-4483-a4c5-2348f1d65f01)

## :memo: Overview

This repository contains the **data analysis** and **transformation pipeline** for creating a Sales Dashboard, designed to visualize key performance metrics for a pharmaceutical sales business. The project involves cleaning and structuring sales data, followed by converting it into a **star schema** format to facilitate the development of a user-friendly dashboard.

## :gear: Key Features

- **Exploratory Data Analysis**: Python code that performs initial analysis, data cleaning, and transformation of raw sales data.
- **Star Schema Conversion**: Scripts to convert the sales data into a **star schema** format for easier reporting and analytics.
- **Sales Dashboard**: A fully functional dashboard built in **Power BI** to track important sales metrics and KPIs.

## :arrow_forward: Data Flow

1. **Data Collection**: The raw sales data is collected from various sources.
2. **Data Cleaning & Transformation**: Using Python, the data is preprocessed to handle missing values, outliers, and structural inconsistencies.
3. **Star Schema Design**: Data is converted into a **star schema** for optimized querying and reporting.
4. **Visualization**: The final dashboard visualizes the KPIs, sales performance, distributor performance, and product insights, among others.

## :snake: Python Code

The Python code in this repository performs the following:

- **Initial Data Analysis**: Loads and inspects the raw sales data, identifying key patterns and anomalies.
- **Star Schema Conversion**: Converts the data into a **star schema** for easier integration with the Power BI dashboard.

You can find the Python scripts in the `scripts/` directory.

### Example of running the data transformation:

```bash
python scripts/transform_data.py
