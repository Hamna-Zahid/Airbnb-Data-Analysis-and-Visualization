# Airbnb Data Analysis and Visualization

## Overview

This project explores and visualizes Airbnb listing data to uncover insights about pricing, availability, and geographic distribution. It involves cleaning the dataset, analyzing key metrics, and generating interactive visualizations to understand trends in the short-term rental market.

## Objectives

- Clean and preprocess Airbnb listing data.
- Handle data-type issues and missing values.
- Generate visual insights using Plotly, Seaborn, and Matplotlib.
- Identify trends in pricing, location, availability, and reviews.

## Dataset

The dataset contains various features about Airbnb listings including:

- `name`, `host_name`, `neighbourhood_group`, `neighbourhood`
- `latitude`, `longitude`, `room_type`
- `price`, `minimum_nights`, `number_of_reviews`
- `last_review`, `reviews_per_month`, `availability_365`

The dataset may include null values in review-related columns and string-formatted price columns that need cleaning.

## Notebook Highlights

### 1. Setup
Installs and imports key Python libraries:
- `pandas`, `numpy`, `re`, `os`
- Visualization: `matplotlib`, `seaborn`, `plotly`, `tabulate`

### 2. Data Cleaning
- Fixes data type issues (`price`, `last_review`)
- Removes columns with high missing data percentage
- Standardizes numeric columns and handles null values

### 3. Exploratory Data Analysis (EDA)
- **Distribution analysis**: Price, reviews, availability
- **Location visualization**: Heatmaps and scatter plots of listing densities
- **Room types**: Breakdown of price vs. availability per room type

### 4. Interactive Visualizations
- Choropleths and scatter maps using Plotly
- Bar plots and line charts for temporal review patterns
- Review trend analysis with date filtering

Key Insights
-Listings in central neighborhoods show higher pricing and availability.
-Private rooms tend to be cheaper but less available year-round.
-Some hosts have high review frequencies despite minimal nights.
