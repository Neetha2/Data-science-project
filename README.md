# Data-science-project.
## COVID-19 Data Science Analysis & Dashboard
This project presents an in-depth data science analysis of COVID-19 trends using a combination of statistical modeling, machine learning, and interactive visualization. It integrates multiple datasets to explore the spread of the virus, demographic correlations, and socio-political influences across U.S. counties and select countries.

## Key Components
Data Integration: Merged primary COVID-19 data (cases, deaths, population) from USAFacts.org with enrichment datasets including employment statistics, U.S. 2020 election results, and census demographic data.

Exploratory Data Analysis: Analyzed trends at the state and county levels, highlighting peaks, patterns, and differences in COVID-19 progression over time.

Global Comparison: Compared U.S. case and death trends with countries such as Japan, Brazil, Germany, China, and Russia using normalized metrics.

Statistical Modeling:

Fitted distributions (log-normal, Poisson, gamma) to assess the shape and spread of COVID-19 cases.

Correlation analysis between case counts and demographic or political variables.

Hypothesis Testing: Conducted hypothesis tests to examine relationships between COVID-19 metrics and factors such as political party affiliation, voter turnout, and age demographics.

Machine Learning:

Applied linear and polynomial regression models to predict future case and death counts.

Evaluated bias vs. variance tradeoffs to balance underfitting and overfitting.

Interactive Dashboard:

Developed using Python Dash.

Features include date range selection, linear/log scale toggling, trendlines, moving averages, and one-week predictive modeling by state.

## Technologies Used
Python: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, dash

Statistical Tools: Correlation analysis, t-tests, regression modeling, distribution fitting

Visualization: Interactive graphs and charts to convey data insights clearly

## Outcomes
This project demonstrates how comprehensive data analysis and visualization can inform understanding of pandemic trends and their links to demographic and political factors. The interactive dashboard allows users to explore the data dynamically and supports informed public health decisions.
