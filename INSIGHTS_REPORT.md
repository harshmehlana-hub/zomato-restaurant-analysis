# Zomato Restaurant Data Analysis — Short Insights Report

## Dataset overview
- Dataset: Zomato Restaurants Data (Kaggle)
- Records: 9,551
- Columns: 21
- Cities represented: 141
- Missing cuisine entries: 9
- Records with aggregate rating 0: 2,148 (treated as not rated for rating-based analysis)

## Data cleaning
1. Inspected missing values in each column.
2. Checked exact duplicate rows and removed any exact duplicates.
3. Reviewed data types and converted key numeric fields (restaurant ID, country code, average cost, rating, votes, and price range) to numeric types.
4. Trimmed leading/trailing whitespace from text fields.
5. Replaced missing cuisine values with `Unknown` to preserve the records for other analyses.
6. Treated aggregate rating 0 as “not rated” and excluded those rows from rating-only comparisons.
7. Screened `Average Cost for two` and `Votes` for outliers using the 1.5×IQR rule. Outliers are flagged for review rather than automatically removed, because unusually high costs or vote counts may be genuine.

## Key insights
- New Delhi has the highest restaurant count in the dataset (5,473), followed by Gurgaon (1,118) and Noida (1,080).
- North Indian is the most frequently mentioned cuisine (3,960 mentions), followed by Chinese (2,735) and Fast Food (1,986).
- Price range 1 is the most common category (4,444 restaurants); price range 4 is the least common (586).
- Among restaurants with a rating above zero, the average rating is approximately 3.44.
- Restaurants with online delivery have a slightly lower average rating than those without online delivery in this dataset; the difference should not be interpreted as a causal effect.
- Restaurants with table booking have a somewhat higher average rating than restaurants without table booking.
- Votes and rating show a positive association (correlation approximately 0.41).
- Average cost and rating have a weak linear relationship (correlation approximately 0.08).

## Visualizations included
1. Restaurant counts by city
2. Most common cuisines
3. Rating distribution
4. Price range distribution
5. Average cost versus rating
6. Online delivery versus rating
7. Table booking versus rating
8. Customer votes versus rating
9. Correlation heatmap

## Limitations
The dataset is observational and may not represent all restaurants or current conditions. Correlation does not prove causation, and IQR outlier flags are not proof that a value is erroneous.

## Dataset source
https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data
