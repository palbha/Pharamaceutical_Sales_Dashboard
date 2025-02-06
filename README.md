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
Open Jupyter Notebook/Lab
```bash
python scripts/transform_data.py
```
## :bar_chart: Dashboard

Below is the image of the final Power BI dashboard that showcases the key sales metrics.

### Dashboard Components

The dashboard is divided into four main components, each providing critical insights to stakeholders:

1. **Executive Dashboard**:  
   - **Purpose**: Displays high-level KPIs such as sales performance, top cities, top products, and top sales teams. It is designed for quick insights into the overall business performance.
   - ![image](https://github.com/user-attachments/assets/5678818d-8b82-4aca-beab-8e08f5889968)

   - **Visuals**:
   - **Filter** : Shows filter on Date, Country 
     - **Key KPI's** : Shows Total Sales , Top Product , Top Product Class , Top sales team & distubutor
     - **Revenue Over Time (Line Chart)**: Shows trends in sales over time.
     - **Revenue by Year & Sales Team (Bar Chart)**: Compares sales performance by year and team.
     - **Revenue by City (Maps )**: Provides sales distribution by geographical location.
     - **Sales by Channel & Year (Stacked Bar Chart)**: Illustrates how different sales channels contribute to yearly sales.
     - **Sales by Subchannel (Donut Chart)**: Displays sales contributions by subchannels.
     - **Sales by Product Class (Donut Chart)**: Shows sales by different product categories.

2. **Distributor Performance**:  
   - **Purpose**: Helps assess the performance of individual distributors. It allows the business to pinpoint areas where distributor performance is either excelling or needs improvement.
   -![image](https://github.com/user-attachments/assets/9dc7bedb-93de-41ac-84fb-b9329cd6aa71)


   - **Visuals**
    - **Filter** : Shows filter on Distrbutor, Country 
    - **Top Distributor by Revenue & by Volume (Bar Chart)** : Identifies highest-grossing distributors.
    - **Revenue by Distributor for each Product Class (Table)** : Identify distributor revenue across different product class
    - **Revenue by Distributor by Year (Table)** : Measures revenue across different distrbutors over time (year).


3. **Sales Team Performance**:  
   - **Purpose**: This page dives deeper into sales performance at a more granular level, showing how teams, channels, and products are contributing to overall performance.
   - ![image](https://github.com/user-attachments/assets/d1299ad6-a9fc-4fa8-afcc-19acc24082ce)


   - **Visuals**
   - **Filter** : Shows filter on Date, Country , Select Sales Team
   - **Key KPI's** : Shows Top Performing Sales Manager & Top performing sales rep
   - **Revenue per Customer(Bar Chart)** : Shows how revenue per customer is varying over Month-Year
   - **Revenue per Sales Rep(Bar Chart)** : Shows in descending order each sales rep & its revenue across the time epriod selected as per filter
   - **Revnue by Sales Team per Product Class(Satcked Bar Chart)** : Shows different Sales Team & their contribution in revenue by each Product Vlass

4. **Product Performance**:  
   - **Purpose**: Provides a detailed look at how individual products are performing in the market, including metrics like sales volume, revenue, and market share.
   - ![image](https://github.com/user-attachments/assets/1bb2d9ad-702b-424e-b22a-7c11c0e97e43)

     
    - **Visuals**
    - **Top Product (Card)** : Shows Top Product by revenue in the selected Class
     - **Revenue by Product (Bar Chart)** : Shows Revenue across each product for th selected product class
     - **Revenue by SubChannel** : Shows revenue within each hannel & subchannel
     - **Reveny & Quantity over Time(Line chart)** : Shows revenue & quntity sold within each selected product class over Time
     - **Revenue by Distbrutiro & Subchannel(Stacked Bar chart)** : Shows revenue for selected product class by Distrubutor & by subchannel

### Dashboard Insights

Each of these components is designed to provide actionable insights for decision-makers. For example:
- The **Executive Dashboard** allows quick assessments of overall sales health, helping executives make timely strategic decisions.
- The **Distributor Performance** page identifies which distributors are underperforming and require further attention.
- **Sales Performance** helps in understanding which sales teams or channels are driving growth and where adjustments might be needed.
- The **Product Performance** page ensures that product teams can track which products are performing well and which need improvement.


## :floppy_disk: Installation

To get started with this project:
Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/sales-dashboard.git
```
:handshake: Contributions
Feel free to contribute to this project! If you have suggestions or improvements, you can fork the repository, make changes, and create a pull request.



