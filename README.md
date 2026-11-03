# COVID-19 Data Analysis

A data analysis project that collects, cleans, and explores publicly available COVID-19 data to understand trends in cases, recoveries, deaths, and testing across regions and time.

## Project overview

The workflow combines Python data extraction and cleaning, SQL-based analysis, and spreadsheet visualization. The project also includes an interactive dashboard for exploring the data.

## Workflow

1. Retrieve COVID-19 data from a public API using Python's `requests` library.
2. Parse JSON responses and extract relevant fields.
3. Clean the data by handling missing values and checking for inconsistencies and duplicates.
4. Use Pandas to transform and aggregate the data.
5. Export state-level data and load it into MySQL for KPI analysis.
6. Aggregate trends by week and month, then use Excel for visualization.

## Questions and indicators

The analysis examines the progression of cases, recoveries, deaths, and tests across locations and time periods. The goal is to make changes and regional differences easier to explore through aggregated data and charts.

## Tools

- **Python:** Requests, JSON, Pandas
- **Database:** MySQL
- **Visualization:** Microsoft Excel
- **Presentation:** Microsoft PowerPoint

## Getting started

### Prerequisites

- Python 3
- Jupyter Notebook (if using the included notebook)
- MySQL, if running the SQL analysis
- Excel or a compatible spreadsheet application for the visualizations

### Setup

1. Clone or download this repository.
2. Install the Python packages used by the project:
   ```bash
   python -m pip install pandas requests
   ```
3. Open the included notebook in Jupyter and run the data extraction and cleaning steps in order.
4. Follow the SQL files and data exports in the repository to load the prepared data into MySQL and reproduce the analysis.

Review the notebook and source files for the specific API endpoint, dataset fields, and database setup.

## Key learnings

- Extracting data from nested JSON structures
- Cleaning missing and inconsistent values
- Transforming and aggregating data with Pandas
- Querying datasets with SQL
- Communicating trends through charts and dashboards

## Author

[Sumidha Kumari Prasad](https://github.com/sumidhakp123)

