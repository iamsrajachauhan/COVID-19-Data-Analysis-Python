# COVID-19-Data-Analysis-Python
This repository presents an analysis of COVID-19 data, with a focus on the factors influencing COVID-19 mortality across various demographics and regions within the United States. The goal of this analysis was to identify key contributors to COVID-19 deaths and offer data-driven recommendations to guide public health strategies and policy-making decisions.

## Project Overview

This project leverages real-world data on COVID-19 deaths and associated conditions from the Centers for Disease Control and Prevention (CDC). The analysis aims to explore the influence of different conditions on COVID-19 mortality, examine geographical disparities, and create predictive models to assist public health officials and policymakers in effectively targeting interventions.

## Repository Structure

- **01 Project Management:** Contains the project brief which outlines the objectives and expectations of the analysis.
- **02 Data:** Contains a PDF file with links to the datasets and files used in the analysis.
- **03 Scripts:** Includes all Python scripts used in the data analysis, structured in Jupyter Notebooks.
- **04 Analysis/Visualizations:** Contains image files of the visualizations generated during the analysis.
- **05 Final Report:** Includes the Tableau Public storyboard as a PDF file, available to view on Tableau Public
   [here](https://public.tableau.com/app/profile/sraja.chauhan/viz/Acheivement6_17186253452660/StudyandExaminationofCOVID-19Data?publish=yes).

## Key Questions 

- Which conditions are most strongly associated with COVID-19 deaths?
- How do COVID-19 death rates vary across different states and age groups?
- What are the geographical patterns in COVID-19 death rates and contributing conditions across the United States?
- How can linear regression and clustering analyses be used to predict and understand COVID-19 mortality?
- What are the temporal trends and seasonal patterns in COVID-19 deaths and contributing conditions?

## Tools Used

- **Python:** The main programming language utilized for conducting data analysis.
- **Pandas:** Used for data manipulation and analysis tasks.
- **NumPy:** Employed for performing numerical computations.
- **Matplotlib & Seaborn:** Tools for creating visual representations of data.
- **Scikit-learn:** Used for building and implementing machine learning models.
- **Statsmodels:** Applied for time series analysis and ARIMA modeling.
- **Geopandas:** Utilized for handling and visualizing geographical data.
- **Plotly:** For crafting interactive data visualizations.
- **Tableau Public:** A tool for developing interactive dashboards and visualizations.


## Visualizations

This project includes various visualizations such as scatter plots, choropleth maps, bar charts, and time-series plots, which illustrate the impact of different conditions on COVID-19 mortality, geographical variations, and temporal trends.

## Analysis 

### Initial Data Exploration

- **Exploration of the dataset:** Understanding the structure and key statistics.
- **Cleaning and preprocessing:** Handling missing values, outliers, and data type conversions.

### Geographical Analysis

- **Choropleth maps:** Visualizing total COVID-19 deaths and death rates per 100,000 population across states.
- **Insights:** Identifying high-impact regions and patterns.

### Linear Regression Analysis

- **Model Building:** Developing a regression model to predict COVID-19 deaths based on the number of mentions of conditions.
- **Performance Evaluation:** Assessing the model using Mean Squared Error (MSE) and R-squared score.

### Cluster Analysis

- **K-means clustering:** Identifying clusters of states with similar COVID-19 impact.
- **Cluster Interpretation:** Analyzing the characteristics and severity of each cluster.

### Time Series Analysis

- **Trend and Seasonality:** Decomposing time series data to identify trends and seasonal patterns.
- **Stationarity Check:** Performing the Dickey-Fuller test and differencing to achieve stationarity.
- **Autocorrelation Analysis:** Using ACF and PACF plots to analyze the autocorrelation structure of the time series data.

## Conclusion

The analysis provided actionable insights into the factors contributing to COVID-19 mortality, highlighting the importance of demographic and condition-specific factors. The findings support targeted public health interventions and resource allocation strategies to better prepare for future health crises.

## Limitations, Potential Biases and Recommendations

- **Provisional Nature of Data:** Data is provisional and conclusions may need revision as finalized data becomes available.
- **Reporting Delays:** Delays in reporting can affect the completeness of recent data.
- **Inconsistent Reporting Standards:** Variability in state-level reporting standards may impact reliability.
- **Multiple Conditions:** Presence of multiple conditions per death complicates analysis.
- **Double Counting Risk:** Deaths involving multiple conditions are counted in each relevant category.
- **Population Data:** Analysis is based on 2020 population data, which may not reflect changes over time.
- **Enhanced Clustering:** Perform clustering analyses on additional conditions and demographics.
- **Predictive Modeling:** Develop models to identify high-risk populations and enhance public health strategies.
