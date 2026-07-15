# Projects

This repository contains tools for preparing assessment data, generating visualizations, and creating summary tables for district and school reporting. The workflow is organized into three Jupyter Notebooks that should be run in order.

## Project 1: Generate Word Report

### 01_clean_data.ipynb
This notebook prepares the source data for analysis. It:

- Cleans and standardizes the raw data
- Removes duplicate records
- Selects and organizes the required columns
- Creates pivot tables for efficient analysis
- Calculates additional metrics such as `met_performance` and `met_growth`
- Exports the cleaned data for use in subsequent notebooks

### 02_plot_charts.ipynb
This notebook generates scatterplots and visualizations from the cleaned data. It:

- Creates performance and growth scatterplots
- Adds configurable performance target lines
- Applies consistent formatting and labeling
- Produces six charts representing different grade bands and district- versus school-level views

### 03_create_tables.ipynb
This notebook creates summary tables to accompany the visualizations. It:

- Converts the analysis data into presentation-ready tables
- Formats metrics for reporting
- Exports tables for inclusion alongside the scatterplots in the final report

## Workflow

Run the notebooks in the following order:

1. **01_clean_data.ipynb** – Prepare and clean the data.
2. **02_plot_charts.ipynb** – Generate charts and visualizations.
3. **03_create_tables.ipynb** – Create summary tables for reporting.

Together, these notebooks transform raw assessment data into polished charts and tables that can be incorporated into district and school reports.