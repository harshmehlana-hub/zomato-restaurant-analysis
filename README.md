# Zomato Restaurant Data Analysis Using Python

## Team
- **Harsh Mehlana**
- **Fenil Parmar**

## Institution
**Indus University — CSE, Semester 5**

## Project Overview
This project performs exploratory data analysis (EDA) on the Zomato Restaurants dataset. It studies restaurant distribution, cuisines, ratings, pricing, customer votes, online delivery, and table-booking availability.

## Objectives
- Analyze restaurant distribution by city.
- Identify the most common cuisines.
- Study restaurant rating distribution.
- Analyze restaurant price ranges.
- Examine the relationship between cost and rating.
- Compare ratings for restaurants with and without online delivery.
- Compare ratings for restaurants with and without table booking.
- Study the relationship between customer votes and ratings.
- Present findings through clear visualizations.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- GitHub

## Dataset
**Zomato Restaurants Data — Kaggle**

Source: https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data

The dataset contains **9,551 restaurant records and 21 columns**.

## Analysis Notebook
The complete analysis is available in `notebooks/Zomato_Restaurant_Analysis.ipynb`.

The notebook covers:
1. Data loading and inspection
2. Data cleaning
3. Restaurants by city
4. Most common cuisines
5. Rating distribution
6. Price range analysis
7. Cost vs. rating
8. Online delivery vs. rating
9. Table booking vs. rating
10. Votes vs. rating
11. Price range vs. rating
12. Correlation analysis
13. Key findings and conclusion

## Key Findings
- **New Delhi** has the largest restaurant representation in the dataset, followed by Gurgaon and Noida.
- **North Indian** is the most frequently mentioned cuisine, followed by Chinese and Fast Food.
- **2,148 restaurants** have a rating of 0; these are treated as **not rated**, rather than zero-star restaurants.
- **Price range 1** is the most common category.
- Restaurants offering **online delivery** have a slightly lower average rating than restaurants without online delivery in this dataset.
- Restaurants offering **table booking** have a higher average rating than restaurants without table booking.
- Customer **votes** show a moderate positive association with rating, while average cost has only a very weak linear association with rating.
- These results describe associations in the dataset and **do not prove causation**.

## Repository Structure
zomato-restaurant-analysis/
├── data/
│   └── README.md
├── notebooks/
│   └── Zomato_Restaurant_Analysis.ipynb
├── proposal/
│   └── project_proposal.md
├── ANALYSIS_SUMMARY.md
├── README.md
├── requirements.txt
└── .gitignore

## Team Contributions
- **Harsh Mehlana:** Project setup, dataset analysis, data cleaning, visualization development, and repository management.
- **Fenil Parmar:** Data exploration, visualization support, interpretation of results, and documentation.

## Reproducibility
The notebook can use a local `data/zomato.csv` file when available. When running in Google Colab without the local dataset, the notebook includes a KaggleHub fallback to obtain the public Kaggle dataset.

## Project Status
**Analysis and documentation completed.**