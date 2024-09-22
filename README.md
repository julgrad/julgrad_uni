# 3 Projects done during university
# Shiny Projects
This repository features a comprehensive analysis of Airbnb listings using R and includes interactive Shiny applications to visualize the data. This project integrates data manipulation, statistical analysis, and interactive visualization, demonstrating the use of advanced R programming techniques and libraries.

## Repository Contents
- `Airbnb Listings through Data.Rmd`: R Markdown file for initial data analysis and visualization.
- `airbnb_3d_plot.html`: Interactive 3D plot of Airbnb listings created using the `plotly` library in a Shiny application.
- `Vienna_Airbnb_Map.html`: Interactive map visualization of Airbnb listings in Vienna, showcasing spatial data handling and interactive mapping in Shiny.
- `airbnbdata.csv`: Dataset used for all analyses and visualizations.

## Libraries and Technologies Used
- `shiny`: For building interactive web applications directly from R.
- `leaflet`: For rendering interactive maps.
- `plotly`: For interactive plotting, including 3D visualizations.
- `dplyr`: For data manipulation.
- `ggplot2`: For creating static visualizations.
- `DT`: For integrating interactive tables.

## Key Features
- **Interactive Data Visualization**: Utilizes `plotly` and `leaflet` within Shiny apps to interactively explore data through visual formats.
- **Data Manipulation and Analysis**: Implements `dplyr` for data cleaning and transformations to prepare data for visualization.
- **Shiny Applications**:
  - **3D Plot Application**: Built with `plotly` to explore data in three dimensions.
  - **Interactive Map**: Developed using `leaflet` to display geographic data interactively.
 
  
# Project_LoretzGini
R project that delves into the analysis of economic inequality through the Lorenz Curve and Gini Coefficient calculations. Additionally, it explores an agent-based model for simulating economic interactions and welfare distribution.

## Files
- `LorenzCurve.R`: Script for plotting the Lorenz curve from given wealth data.
- `GiniCoefficient.R`: Function to calculate the Gini coefficient.
- `EYSM.R`: Extended Yard Sale Model (EYSM) simulation.
- `MonteCarloSimulation.R`: Monte Carlo simulations to explore different economic scenarios.

## Libraries Used
- `ggplot2`: Utilized for generating all plots within the project.

## Key Concepts
- **Lorenz Curve**: Provides a graphical representation of the distribution of wealth within a population.
- **Gini Coefficient**: Measures economic inequality within a population.
- **Agent-based Modeling**: Simulates economic transactions to study the effects on wealth distribution.
- **Monte Carlo Simulation**: Used to project the impact of different economic parameters over multiple iterations.

# Data Analysis
 R project focusing on statistical data analysis techniques using several complex R libraries and functions to derive insights from various datasets.
## Libraries Used
- `dplyr`: For data manipulation.
- `ggplot2`: For data visualization.
- `margins`: For calculating marginal effects in regression models.
- `estimatr`: For robust statistical estimations.

## Key Techniques
- **Regression Analysis**: Logistic regression, Linear Regression Discontinuity.
- **Data Transformation**: Creating subsets, transforming variables.
- **Statistical Testing**: Shapiro-Wilk test, Wilcoxon rank-sum test.
- **Visualization**: Scatter plots, bar plots, and boxplots.

## Highlights
- **Logistic Regression with `glm()`**: Used for modeling binary outcome variables in admissions data.
- **Linear Regression Discontinuity Analysis**: Employed to assess the impact of the legal drinking age on alcohol-related deaths.
- **Robust Estimation with `lm_robust()`**: Applied to study the effects of concealed weapons laws on violent crime rates.
