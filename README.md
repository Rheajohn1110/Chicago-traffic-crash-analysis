# Chicago Traffic Crash Analysis

## Overview
This project, conducted by Group Beta for the Data Management and Big Data course (ALY6110) at Northeastern University, focuses on analyzing traffic crash data to provide insights into traffic safety and congestion on Chicago streets.

## Dataset
The analysis utilizes two datasets sourced from the City of Chicago's open data portal:
- **Traffic Crash Data:** Contains records of traffic crashes on Chicago streets, detailing occurrences and conditions during incidents.
- **People Involved in Crashes Data:** Details demographic and injury severity information for individuals involved in the crashes.

These datasets were combined using the common key, CRASH_ID, resulting in a merged dataset with over 1.8 million records.

## Objectives
- **Analyze Traffic Crash Data:** To identify patterns and trends related to various factors like weather, lighting, and traffic control devices.
- **Examine People Involved in Crashes:** To understand the impact of demographic factors and injury severity.
- **Generate Actionable Insights:** Provide data-driven insights to improve traffic safety measures.
- **Create an Interactive Dashboard:** Develop a dashboard to visualize key findings for easy access by decision-makers and the public.

## Tools Used
- **Azure:** For creating and managing data storage.
- **Databricks:** Used for data processing and analysis due to its powerful big data handling capabilities and integration features.
- **Delta Lake:** To manage batch and real-time data processing.

## Process
1. **Data Ingestion:** Data is loaded into an Azure storage account and ingested into Databricks.
2. **Data Cleaning:** Data is cleaned and preprocessed to ensure accuracy and relevance.
3. **Data Analysis:** Conducted through Databricks using SQL and Python to uncover trends and patterns.
4. **Dashboard Development:** An interactive dashboard is created to display the analysis results.

## Results
Key insights include the identification of high-risk areas, the impact of weather and lighting conditions on crash rates, and demographic analysis of individuals involved in crashes. These findings are visualized through a series of graphs and charts available in the project's dashboard.

## Dashboard
Access the interactive dashboard [here](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3190617666491842/2373282331786799/6555990026723924/latest.html).

## Team Members
- Sanchi Gupta
- Sankalp Biswal
- Siddhant Viswanath
- Rhea John Thoppil
- Krutikkumar Patel

## References
- Data sourced from the [City of Chicago Data Portal](https://data.cityofchicago.org/).

## How to Run
Instructions for setting up and running the project:
1. Set up an Azure storage account and create a container named 'traffic-data'.
2. Upload the datasets to the Azure blob storage.
3. Set up a Databricks cluster and attach a notebook.
4. Follow the steps in the notebook to perform the analysis.

Feel free to clone this repository and explore traffic crash analysis for your use case!
