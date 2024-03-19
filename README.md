# Car Pricing Project: Used Car Price Analysis for Automobile Dealers
## Project Overview
This project is part of a practical application initiative designed for an AI/ML course at UC Berkeley, targeting automobile dealers aiming to optimize their inventory pricing strategies. Through this exercise, we delve into a comprehensive dataset to unveil critical insights into factors affecting used car prices, focusing on the impact of a vehicle's manufacturing year ('year') and mileage ('odometer').

## Objective
Our primary goal is to dissect the relative influence of the manufacturing year and mileage on the market price of used vehicles. Understanding these dynamics will empower automobile dealers to make informed decisions, ultimately enhancing their pricing strategies and competitiveness in the used car market.

## Data Cleaning and Preprocessing
The dataset, sourced from a collection of used car listings, undergoes a series of preprocessing steps to ensure accuracy and relevance:

Removal of unnecessary identifiers such as 'id' and 'VIN'.
Handling of missing values and anomalies.
Categorization of continuous variables for a more detailed analysis.
Creation of a combined 'ManufacturerModel' feature for a granular understanding of model-specific pricing trends.
## Analysis
The analysis consists of the following components:

### Summary Statistics: 

We provide a summary of numerical and categorical features to establish a baseline understanding of the dataset.

### Regression Analysis: 
Linear and polynomial regression models are employed to assess the effects of 'year' and 'odometer' on 'price', across the top-selling vehicle models.

### Visualization: 
Through histograms, boxplots, scatter plots, and heatmaps, we visualize data distributions and relationships, offering intuitive insights into the factors driving car prices.

# Key Findings
### Relative Importance: 

Analysis reveals the weighted impact of a car's year and mileage on its price.
### Top Models: 
A focused examination of the top-selling models provides specific insights applicable to high-volume segments.
### Usage
This analysis is particularly beneficial for automobile dealers aiming to strategically price their inventory.
Understand market trends and consumer preferences.
Optimize stock based on models that provide the best value or return.
# Conclusion
Year and odometer reading matter a lot compared to other car features. Combined, they are responsible for over a 3rd of price variation in used cars. But between the two, year is significantly more impactful on price than odometer reading, according to the findings in this large dataset. 
