# Unemployment Analysis in India

## Project Overview
This project aims to analyze the unemployment rate in India, focusing on various regions and how the rates have changed over time, particularly in the context of the COVID-19 pandemic. The analysis involves data cleaning, exploratory data analysis (EDA), and visualization to identify trends, regional disparities, and the impact of significant events.

## Dataset
The dataset used for this analysis is `Unemployment in India.csv`. It contains information about unemployment rates, estimated employment, and labor participation rates across different regions in India.

### Columns:
- `Region`: State or Union Territory in India.
- `Date`: Date of observation.
- `Frequency`: Frequency of data collection (e.g., Monthly).
- `Estimated Unemployment Rate (%)`: Percentage of the labor force that is unemployed.
- `Estimated Employed`: Number of people estimated to be employed.
- `Estimated Labour Participation Rate (%)`: Percentage of the working-age population that is in the labor force (employed or actively seeking employment).
- `Area`: Classification of the area (e.g., Rural, Urban).

## Key Analyses Performed
1.  **Data Loading and Initial Inspection**: Loaded the dataset and performed initial checks for structure, data types, and missing values.
2.  **Data Cleaning**: Handled missing values by dropping rows with `NaN` values and standardized 'Frequency' column.
3.  **Descriptive Statistics**: Generated summary statistics to understand the distribution of key numerical features.
4.  **Missing Value Visualization**: Visualized the distribution of missing values using heatmaps and bar plots.
5.  **Regional Unemployment Analysis**: Calculated and visualized the average unemployment rate and labor participation rate per state.
6.  **Unemployment Rate Distribution**: Identified states with the highest and lowest average unemployment rates.
7.  **Relationship between Unemployment and Labor Participation**: Explored the relationship between unemployment rate and labor participation rate using scatter plots.
8.  **Impact of COVID-19**: Analyzed the unemployment rate before and after March 2020 (considered as the onset of the COVID-19 pandemic) to understand its impact.

## How to Use This Notebook
1.  **Clone the Repository**: Clone this GitHub repository to your local machine.
2.  **Open in Google Colab**: Upload the notebook (`.ipynb` file) to Google Colab.
3.  **Upload Dataset**: Ensure the `Unemployment in India.csv` file is present in the Colab environment (e.g., by uploading it or mounting Google Drive).
4.  **Run Cells**: Execute the code cells sequentially. The notebook is structured to perform data loading, cleaning, analysis, and visualization steps in order.
5.  **Interpret Results**: Review the generated plots and printed outputs to understand the unemployment trends and patterns.
