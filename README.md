# **Web Scraping and Analysis: Movie titles**

## **Executive Summary**

This repository contains Python-based data analysis projects focused on movie performance and trends, using real-world data scraped from Metacritic and IMDB. Each subproject demonstrates data cleaning, database querying, visualization, and storytelling using pandas, matplotlib, and MongoDB. The main objective is to uncover patterns in how movie characteristics relate to critical and commercial success.

## **Business Problem**

The main question for this exploration of data is:
- Is there any relation between the performance of movies in a certain year and the gender/rating they belonged to?
- Are sales related to the overall performance of movies in a year?
- Are bigger budgets in movies equivalent to higher revenue?

## **2018 Movie Analysis**

Goal: Explore how movie genre, budget, and sales relate to overall performance.
Highlights
- Web-scraped and merged Metacritic movie data into MongoDB Atlas.
- Created visualizations for runtime, genre trends, and cumulative gross sales.
- Built custom formatters for readable financial scales (K, M, B, T).
- Found that bigger budgets don’t always guarantee higher revenue.

## **2017 Movie Analysis**

Goal: Investigate whether higher budgets and better Metacritic scores lead to stronger opening weekend revenues.
- Combined IMDB and Metacritic datasets for 2017 releases
- Analyzed budget vs. opening revenue and rating vs. revenue correlations
- Discovered that critical reception correlates moderately with box-office success, but high budgets alone don’t ensure profitability

## **Methodology**
1. Web Scraping:
  - Used requests, BeautifulSoup, and regular expressions to extract titles, ratings, budgets, and revenues from public Metacritic and IMDb pages.
4. Data Cleaning & Storage:
  - Normalized scraped data into structured formats using pandas.
  - Stored data in MongoDB Atlas for scalable querying and filtering.
3. Exploratory Data Analysis (EDA):
  - Conducted descriptive analysis with pandas and matplotlib.
  - Built scatterplots, histograms, and correlation matrices to visualize trends.
  - Investigated outliers, genre-specific behaviors, and inconsistencies between critic and audience ratings.

## **Methodology**
- Python – Data scraping, wrangling, and visualization
- Libraries: pandas, BeautifulSoup, requests, re, matplotlib
- Database: MongoDB Atlas
- Data Cleaning: Regular expressions, type conversion, handling missing values
- Analysis Techniques: Correlation analysis, outlier detection, regression basics
- Visualization: Comparative box plots, scatter plots, and trend charts

## **Results (So far)**
- Successfully merged two large movie datasets (IMDb + Metacritic) across multiple years.
- Discovered that while critical acclaim tends to correlate with opening performance, it doesn’t always sustain long-term profitability.
- Genres like drama and action show more stable returns, whereas comedy and experimental films exhibit higher volatility in revenue outcomes.
- Built a MongoDB pipeline for future automated updates and scalability.

## **Next Steps**
1. Add 2020–2024 datasets to observe post-pandemic box-office recovery patterns.
2. Incorporate sentiment analysis from review text for qualitative insights.
3. Deploy Power BI or Streamlit dashboard for interactive exploration.
4. Experiment with predictive modeling to estimate box-office performance based on critic ratings and budgets.
5. Create relevant recommendations and convey them through storytelling to members who would find this relevant.
