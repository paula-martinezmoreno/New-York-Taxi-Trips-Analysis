# New-York-Taxi-Trips-Analysis
This repository contains code analyzing New York City taxi trips dataset using Apache Spark. The dataset covers over 1 billion individual taxi trips in the city from January 2009 through January 2023. The analysis focuses on exploring various aspects of taxi traffic, including seasonalities, geographical patterns, and the impact of external factors such as the COVID-19 pandemic.

## Dataset

The New York City Taxi & Limousine Commission provides a detailed historical dataset covering yellow and for-hire vehicle (FHV) taxi trips. The dataset is available from the [New York City Government website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). It consists of Parquet files for each taxi service (yellow, green, FHV) and each calendar month. 

## Tools and Libraries

- Apache Spark: Used for distributed data processing and analysis.
- Python: Programming language for scripting and analysis.
- GeoPandas, Plotly, Matplotlib, Seaborn: Libraries for data visualization.
- IPyLeaflet: Library for interactive map visualization.
