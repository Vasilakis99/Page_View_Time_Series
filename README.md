# Page View Time Series Visualizer

## Overview
This project involves visualizing time series data of page views on the freeCodeCamp forum. It spans from May 2016 to December 2019, focusing on identifying trends and patterns in forum activity.

## Dataset
The dataset `fcc-forum-pageviews.csv` contains the following columns:
- `date`: The date of the record.
- `value`: The number of page views on that date.

The data is structured to facilitate time series analysis and visualization.

## Methodology
### Data Cleaning and Preparation
Initial steps include importing and cleaning the data, with a specific focus on parsing dates and setting the index column to 'date'.

### Visualization
The project includes the creation of various visualizations:
1. **Line Chart**: A line chart titled 'Daily freeCodeCamp Forum Page Views 5/2016-12/2019' visualizing the number of page views over time.
2. **Bar Chart**: A bar chart showing average daily page views for each month, grouped by year. This includes a legend with month labels and an appropriate title.

## Findings
Through the visualizations, the project reveals:
- Trends and patterns in the forum's daily activity.
- Seasonal variations and yearly changes in page views.

## How to Use
To replicate the analysis and visualizations:
1. Ensure Python, Jupyter Notebook, and necessary libraries (like Matplotlib) are installed.
2. Clone the repository and navigate to the project directory.
3. Open the `Page View Time Series Visualizer.ipynb` notebook.
4. Execute each cell to generate the visualizations.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
