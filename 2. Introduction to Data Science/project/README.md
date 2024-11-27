# README for Valencia Tourism Analysis Notebook (ValenciaEDA.ipynb)
# Overview
This notebook provides an in-depth analysis of Valencia's tourism landscape, focusing on the impact of Airbnb data from 2010 to the present. 
It explores the evolution of accommodations, pricing trends, neighborhood dynamics, and customer preferences based on review comments. 
The findings aim to offer insights into how the rise of Airbnb has shaped the local economy and community dynamics in Valencia.

# Contents
## Import Dependencies
Import dependencies and setting options.

## Import Data
Import the data and generate pandas dataframes.

## Visualize Data
Descriptive statistics over the imported dataframes to have a first glimpse of the data format, types and flaws.

## Data Preparation
Data Manipulation, Cleaning and Wrangling. In this section we pre-process the data for retrieving the price correlation matrix and for future use.

## Review WordCloud
Wordcloud geenrated to illustrate the most commont review words.

## Evolution of listings
Number of listing per year.

## Evolution of reviews
Number of reviews per year.

## Distribution per Neighborhoods
Distribution of listing per neighborhood with corresponding mean price. In this section, barcharts have been created to illustrate current price and future price scenario.

## Distribution per Room Type
Distribution per Room Type with corresponding price and number of reviews (both in absolute and relative terms).

## Evolution of the Average price overtime by Neighborhoods
Linecharts per Neighborhoods displaying the historical evolution of mean prices and number of reviews. 

# Requirements
To run this notebook, you will need the following Python libraries:
-pandas
-numpy
-matplotlib
-seaborn
-wordcloud

You can install these libraries using pip:
[bash] pip install pandas numpy matplotlib seaborn wordcloud


# Usage
Clone or download the repository containing the notebook.
Open the notebook in your preferred Jupyter environment (e.g., Jupyter Notebook, JupyterLab).
Run the notebook cells sequentially to execute the analysis and generate visualizations.
Review the findings and insights provided throughout the notebook.