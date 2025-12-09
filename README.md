# Gun Violence in America: Exploratory Data Analysis (2013–2018)
## Project Summary
This project provides a comprehensive exploratory analysis of gun-violence incidents across the United States from 2013 to 2018. Using incident-level data sourced from the Gun Violence Archive, the goal is to identify where, when and how gun-violence events concentrate and how injuries and fatalities contribute to total casualties.

The analysis evaluates geographic patterns, temporal trends and incident characteristics to support data-driven decisions for prevention strategies, resource allocation and public-safety planning. Clustering and descriptive analytics were applied to uncover patterns that may help classify states and incidents into distinct risk profiles.

This project forms part of the CareerFoundry Data Analytics program.

## Key Questions

The analysis investigates the following questions based on factual attributes available in the dataset:
1. Where are gun-violence incidents and casualties concentrated across states?
2. How do fatalities and injuries contribute to total casualties?
3. Are there temporal patterns across years, months or seasons?
4. Which states show the highest and lowest burden of gun-violence incidents and casualties?
5. What types of incidents occur most frequently?
6. Can incidents or states be grouped into meaningful clusters (risk profiles)?
7. How do severity indicators such as number killed, number injured and guns involved vary across clusters or locations?
8. These research questions guide the exploratory analysis and storyboard development.

## Folders
* 01 Project Management: Contains the project brief, planning notes and business questions that define the analytical scope and objectives.

* 02 Data: Includes two subfolders.
(Data files are not uploaded to GitHub due to size restrictions.)

  * Original Data: Raw datasets containing incident-level gun-violence information.

  * Prepared Data: Cleaned and transformed datasets ready for analysis and visualization.

* 03 Scripts
Python code executed in Jupyter notebooks. Scripts include:
  * Data cleaning
  * Feature engineering
  * Temporal analysis
  * Exploratory visualizations
  * Correlation analysis
  * Clustering (K-Means)
  * Export of prepared datasets to CSV

* 04 Analysis: Contains visualizations produced during exploratory and explanatory phases, including:
  * Heatmaps
  * Temporal line charts
  * State-level bar charts
  * Cluster segmentation charts
  * Storyboard visual elements

* 05 Sent to Client: Final presentation files summarizing insights, conclusions and recommended next steps.

## Code Overview

Code was written in Python and executed in Jupyter notebooks using the following libraries:

* Pandas: Data cleaning, manipulation and aggregation
* NumPy: Numerical computations
* OS: File-path and directory management
* Matplotlib.pyplot: Line charts, bar charts and incident-trend visualizations
* Seaborn: Heatmaps and statistical visualizations
* SciPy / Statsmodels: Statistical methods where required
* Scikit-Learn: K-Means clustering and scaling for segmentation analysis

## Summary of Methods

* Data Cleaning: Standardized dates, handled missing values and created new variables such as total casualties.
* Exploratory Analysis: Identified spatial and temporal trends and evaluated severity patterns.
* Visualization: Used Tableau and Python to generate descriptive visuals.
* Clustering: Applied K-Means to categorize incidents by severity and casualty patterns.
* Temporal Analysis: Line charts and seasonal comparisons to assess changes from 2013 to 2018.

## Disclaimer
All insights are derived strictly from publicly available gun-violence incident data. No personally identifiable information is included. This project was created for educational purposes as part of CareerFoundry’s Data Analytics program.
