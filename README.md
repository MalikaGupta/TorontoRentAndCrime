# TorontoRentAndCrime
Analyzing the correlation between rental prices and crime rates in Toronto's six boroughs using scraped Kijiji listings and Toronto Police crime data.
## Toronto Rental Prices and Crime Analysis: A Data-Driven Approach to Finding Safe and Affordable Housing
### Introduction and Background
As I plan to live in Toronto for the next few years, finding a safe and affordable place to rent is my top priority. To achieve this, I've embarked on a data-driven project that leverages rental postings from platforms like Kaggle, TorontoRentals.ca, and Kijiji, combined with Major Crime Indicators data from the Toronto Police Public Safety Data Portal. This project aims to map rental prices to crime data across different Forward Sortation Areas (FSAs) in Toronto, helping prospective renters make informed decisions about where to live.

### Related Links:
Kijiji - Toronto Apartments & Condos for Rent (https://www.kijiji.ca/b-apartments-condos/city-of-toronto/page-1/c37l1700273?address=Toronto%2C%20ON&ll=43.653226%2C-79.3831843&radius=50.0)
Kaggle - Toronto Apartment Price Dataset (https://www.kaggle.com/datasets/rajacsp/toronto-apartment-price)
Toronto Police - Major Crime Indicators Open Data (https://data.torontopolice.on.ca/datasets/0a239a5563a344a3bbf8452504ed8d68_0/explore)
The project utilizes over 3,000 rental property listings and 396,735 crime records from the Major Crime Indicators dataset, focusing on data from the past four years (2020 onwards) to reflect the most current and relevant information.

### Objectives and Goals
The primary objective of this project is to explore and visualize the relationship between rental prices and crime rates across Toronto’s neighborhoods. The specific questions I aim to answer include:

What are the average rental prices in different FSAs of Toronto?
How do crime rates vary across these FSAs?
Is there a correlation between higher rental prices and lower crime rates, or vice versa?
By addressing these questions, this project seeks to assist potential renters by providing insights into the safety and affordability of various Toronto neighborhoods.

### Datasets
1. Rental Prices Dataset
Source: Scraped from Kijiji using Python and from Kaggle.
Size: Over 3,000 rows for rental property listings.
Location: Six boroughs of Toronto.
Variables: Includes rent prices, number of beds and baths, square footage, FSAs, and listing links.
2. Major Crime Indicators Dataset
Source: Toronto Police Public Safety Data Portal
Collector/Funder: Collected by the Toronto Police Service.
Size: 396,735 records spanning from 2014 onwards, narrowed down to data from 2020 onwards.
Location: City of Toronto.
Variables: Includes crime types, crime rates, FSAs, and time periods.
These datasets form the foundation for analyzing and visualizing the correlation between rental prices and crime rates, helping achieve the project's goals. However, potential limitations include the accuracy and completeness of the rental listings data.

## Project Structure
###  Data Cleaning and Preparation:

Handling missing data, especially in the rental dataset.
Filtering crime data to focus on records from 2020 onwards.
Aggregating data by FSA using Geocod.io API.

### Exploratory Data Analysis:

Visualizing the geographical distribution of rental prices and crime rates.
Identifying patterns and outliers within the datasets.

### Correlation Analysis:

Analyzing the relationship between rental prices and crime rates.
Evaluating the strength and direction of the correlation.

### Visualization and Reporting:

Creating interactive maps to display crime rates and rental prices by FSA on Tableau.
Developing dashboards to allow users to explore data by various filters (e.g., crime type, rental price range).

## Conclusion and Recommendations:

Summarizing key findings and insights.
Providing recommendations for prospective renters based on the analysis.
Conclusion
This project aims to provide valuable insights into the Toronto rental market by examining the interplay between rental prices and crime rates. By mapping these variables geographically, the project offers a visual and data-driven guide to help renters find neighborhoods that balance safety and affordability.

