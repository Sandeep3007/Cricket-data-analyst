# Cricket Team Selection Analysis Project

## Overview
This project focuses on using data analysis techniques to select the best playing 11 for a cricket team. The selection criteria are based on the team's ability to score at least 180 runs on average and defend 150 runs on average. The team is divided into five categories: Openers, Middle Orders, Finishers, All-rounders, and Fast Bowlers. Each category has specific parameters that players must meet to be considered for selection.

## Data Source
The data used for this analysis was scraped from a reliable source and stored in a JSON format. The JSON file was then processed to clean the data, removing special characters from player names, and converted into a CSV format for further analysis.

## Tools Used
- Python for data cleaning and preprocessing.
- MS Power BI for data visualization, dashboard creation, and analysis.
- DAX (Data Analysis Expressions) queries for creating measures and parameters for player selection.

## Methodology
1. **Data Cleaning**: Special characters in player names were removed using pandas in Python.
2. **Data Transformation**: The cleaned data was imported into MS Power BI for further transformation and analysis.
3. **Dashboard Creation**: A dashboard was created in MS Power BI to visualize various parameters and metrics related to player performance.
4. **Data Modelling**: Parameters were defined using DAX queries to evaluate player performance against selection criteria.
5. **Player Selection**: Based on the analysis of the dashboard and evaluation of player performance, the best playing 11 was selected.

## Parameters for Player Selection
- **Openers**: Batting average > 30, Strike rate > 140, Boundary % > 40
- **Finishers**: Batting average > 25, Strike rate > 135, Average balls faced > 12
- **Middle Orders, All-rounders, Fast Bowlers**: Specific parameters based on their roles and responsibilities.

## Readme Contents
1. Overview
2. Data Source
3. Tools Used
4. Methodology
5. Parameters for Player Selection
6. Instructions for Running the Project
7. Results and Insights

## Conclusion
This project demonstrates how data analysis techniques can be applied to optimize the selection of a cricket team. By defining specific parameters and evaluating player performance, teams can make informed decisions to maximize their chances of success on the field.
