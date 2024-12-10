# Road Accidents 2020 - Regulatory Affairs

## Overview
This project focuses on analyzing road accident data for 50 cities in India in 2020, sourced from [data.gov.in](https://data.gov.in/catalog/road-accidents-india-2020). The analysis aims to explore the causes, outcomes, and trends in road accidents to assist in policymaking and improve road safety measures.

## Dataset Description
The dataset contains crucial information about road accidents categorized by various causes and their outcomes. Below is a detailed description of the columns in the dataset:

### Columns:
1. **Million Plus Cities**:  
   The names of the cities with a population of over a million.
   
2. **Cause Category**:  
   Five primary categories indicating the broad classification of accident causes:  
   - Traffic Control  
   - Junction  
   - Road Features  
   - Impacting Vehicle/Object  
   - Weather Conditions  

3. **Cause Subcategory**:  
   Further detailed classification of the exact causes within each category.  
   
4. **Outcome of Incident**:  
   Indicates whether the incident resulted in accidents, injuries, or deaths.  

5. **Count**:  
   The count (in millions) for each incident type.

## Objective
The goal of this project is to analyze the data to:
- Identify trends and patterns in road accidents across various cities.
- Classify accidents based on the cause and its subcategory.
- Examine the outcomes of incidents (injuries, deaths, accidents).
- Provide insights to inform policymaking and regulatory affairs regarding road safety.

## Analysis Steps
1. **Data Preprocessing**:  
   Clean the data by handling missing values, converting categorical data to appropriate formats, and standardizing columns for better analysis.
   
2. **Exploratory Data Analysis (EDA)**:  
   Perform EDA to identify trends, such as:
   - Most common accident causes by category and subcategory.
   - The number of accidents, injuries, and deaths in different cities.
   - Visualizing accident trends over the year.

3. **Visualizations**:  
   Create visualizations to provide clear insights into the dataset:
   - Pie charts for cause categories.
   - Bar charts for accidents and injuries by city.
   - Heatmaps and histograms for identifying patterns across different variables.

4. **Insights and Recommendations**:  
   Derive key insights and actionable recommendations to improve road safety, such as focusing on high-risk accident categories or cities with higher accident rates.

## Files Included
- **accident_data.csv**: The main dataset containing road accident details.
- **analysis_script.py**: The Python script for cleaning, analyzing, and visualizing the data.
- **visualizations/**: A folder containing various charts and graphs generated during the analysis.

## Future Work
Integration with external sources to enhance data accuracy.
Predictive analysis for road accident trends in future years.
Incorporate more granular data (e.g., accident severity, weather conditions) for deeper insights.

## Acknowledgments
Dataset sourced from kaggle.com



