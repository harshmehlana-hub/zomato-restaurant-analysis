# Zomato Analysis Summary

## Dataset
- 9,551 restaurant records
- 21 columns
- 141 cities
- 15 country codes
- 9 missing cuisine values
- 2,148 restaurants with rating 0 (treated as not rated)

## Main findings
1. New Delhi has the largest restaurant representation (5,473), followed by Gurgaon (1,118) and Noida (1,080).
2. North Indian is the most frequently mentioned cuisine (3,960 mentions), followed by Chinese (2,735) and Fast Food (1,986).
3. Among rated restaurants, the mean rating is about 3.44 and the median is 3.40.
4. Price range 1 is the most common category (4,444 restaurants); price range 4 is the least common (586).
5. Online-delivery restaurants average about 3.38 versus 3.47 without delivery; the difference is small and does not indicate that delivery itself causes ratings to change.
6. Table-booking restaurants average about 3.59 versus 3.41 without table booking.
7. Votes and rating have a moderate positive association (about 0.41 correlation).
8. Average cost and rating have a very weak linear relationship (about 0.08 correlation).
9. Average rating rises across price ranges in this dataset.

## Methodology note
Rating 0 is treated as not rated and excluded from rating-based comparisons. Associations are not interpreted as causation.
