# War Data Analysis

## Project Overview

This project involves analyzing data on global conflicts from 1989 to 2022. The dataset contains information on the number of deaths in various countries during different conflicts. The primary objective is to identify trends and patterns in conflict-related fatalities across different regions and subregions, and to examine how the variability in the intensity of conflicts (measured by the standard deviation of annual deaths) relates to the total number of deaths.

## Data

Link to dataset: https://www.kaggle.com/datasets/willianoliveiragibin/war-and-peace

### Features

The dataset includes the following columns:

- **Country**: The country where the conflict occurred.
- **Code**: The country code.
- **Year**: The year the data was recorded.
- **Deaths**: The number of deaths reported for that year.

### Target

- **Total Deaths**: The total number of deaths over the entire conflict period.

## Methods

### Data Preprocessing

- **Data Cleaning**: The dataset was cleaned by addressing missing values and converting the country column to a categorical data type to optimize memory usage.
- **Merging Datasets**: A country-to-region dataset was merged with the main dataset to facilitate regional and subregional analysis.

### Exploratory Data Analysis (EDA)

- **Time Series Analysis**: Analyzed death tolls over time by region to detect patterns and spikes, particularly in relation to significant historical events like the Arab Spring and the Syrian Civil War.
- **Regional and Subregional Trends**: Conducted a detailed analysis of death tolls across different regions and subregions, revealing variations in conflict types and intensity across geographic areas.
- **Correlation Analysis**: A Pearson correlation coefficient was calculated to examine the relationship between the variability of annual deaths (standard deviation) and the total death toll, revealing a strong positive relationship.

### Visualizations

- **Trend Analysis by Region**: Visualized death toll trends over time for different regions and subregions to highlight key patterns.
- **Subregional Analysis**: Created plots for subregions within Asia to explore variations in conflict intensity and death tolls.

## Results

- **Key Findings**:
    - There is a strong positive correlation between the standard deviation of annual deaths and the total death toll, indicating that conflicts with higher variability in death tolls tend to result in higher overall fatalities.
    - Intrastate conflicts in the Middle East saw significant spikes in the 2010s, coinciding with the Arab Spring and the Syrian Civil War.
    - Non-state conflicts have become more prevalent in the Americas over the past decade, although the data lacks subregional breakdowns to provide more granular insights.

## Conclusion

This project demonstrates the application of data analysis techniques to explore the impact of global conflicts. The analysis highlights the importance of examining both regional and subregional trends to understand the dynamics of conflict intensity and fatalities. The strong correlation between variability in death tolls and total deaths suggests that conflicts with unpredictable spikes in violence tend to be the most deadly.
