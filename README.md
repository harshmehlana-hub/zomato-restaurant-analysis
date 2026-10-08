# Zomato Restaurant Data Analysis Using Python

## Project Overview

This project focuses on the exploratory data analysis of a Zomato restaurant dataset using Python.

The purpose of the project is to examine restaurant-related information such as locations, cuisines, ratings, pricing, customer votes, online delivery, and table booking facilities. The dataset is explored using data cleaning, statistical analysis, and visualization techniques to identify useful patterns and insights.

## Team Members

- Harsh Mehlana
- Fenil Parmar

**Course:** Computer Science and Engineering  
**Semester:** 5th Semester  
**Institution:** Indus University

## Dataset

The project uses the **Zomato Restaurants Data** dataset available on Kaggle.

Dataset source:

https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data

The dataset contains information about restaurants including:

- Restaurant name
- City and location
- Cuisines
- Average cost for two people
- Price range
- Aggregate rating
- Number of votes
- Online delivery availability
- Table booking availability

The dataset contains **9,551 restaurant records and 21 columns**.

## Project Objectives

The main objectives of this project are:

1. Analyze the distribution of restaurants across different cities.
2. Identify the most frequently occurring cuisines.
3. Study the distribution of restaurant ratings.
4. Analyze restaurants according to their price ranges.
5. Examine the relationship between restaurant cost and rating.
6. Compare restaurants based on online delivery availability.
7. Compare restaurants based on table booking availability.
8. Study the relationship between customer votes and restaurant ratings.
9. Use visualizations to present important patterns in the dataset.
10. Summarize the findings obtained from the analysis.

## Technologies and Libraries

The project uses the following tools and Python libraries:

- **Python**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook / Google Colab** — analysis environment
- **GitHub** — project version control and collaboration

## Data Analysis

The analysis includes the following sections:

### 1. Data Inspection and Cleaning

The dataset is examined for:

- Missing values
- Duplicate records
- Categorical values
- Rating values
- Data consistency

For rating-based analysis, restaurants with an aggregate rating of `0` are treated as **not rated** rather than as zero-star restaurants.

### 2. Restaurant Distribution by City

The number of restaurants in different cities is compared to identify locations with the largest restaurant representation.

### 3. Most Common Cuisines

Cuisine information is analyzed to identify the cuisines that appear most frequently in the dataset.

### 4. Rating Distribution

The distribution of restaurant ratings is visualized to understand the overall rating pattern.

### 5. Price Range Analysis

Restaurants are grouped according to their price range to determine the most common pricing category.

### 6. Cost vs Rating

The relationship between the average cost for two people and restaurant ratings is examined using a scatter plot and correlation analysis.

### 7. Online Delivery Analysis

Restaurants with and without online delivery are compared based on their average ratings.

### 8. Table Booking Analysis

Restaurants with and without table booking facilities are compared based on their average ratings.

### 9. Votes vs Rating

Customer votes are compared with restaurant ratings to examine whether restaurants receiving more votes tend to have different rating patterns.

### 10. Correlation Analysis

A correlation heatmap is used to visualize relationships among selected numerical variables.

## Key Findings

The analysis provides several observations from the dataset:

- **New Delhi** has the largest restaurant representation in the dataset.
- **North Indian** is the most frequently mentioned cuisine.
- A significant number of restaurants have a rating value of `0`, which is treated as not rated.
- **Price range 1** is the most common price category.
- Restaurants with and without online delivery show different average rating patterns.
- Restaurants with table booking have a different average rating compared with restaurants without table booking.
- Customer votes show a positive association with restaurant ratings.
- Average cost has only a weak linear relationship with restaurant rating.

These findings describe patterns in the dataset and should not be interpreted as proof of cause-and-effect relationships.

## Project Structure

```text
zomato-restaurant-analysis/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Zomato_Restaurant_Analysis.ipynb
│
├── proposal/
│   └── project_proposal.md
│
├── ANALYSIS_SUMMARY.md
├── FAQ.md
├── README.md
├── requirements.txt
└── .gitignore
