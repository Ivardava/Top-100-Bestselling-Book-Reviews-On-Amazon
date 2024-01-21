# Top 100 Bestselling Book Reviews on Amazon

## Objectives

Genre and Pricing Analysis:

1. Visualize top genres using a treemap and analyze pricing trends for the top 10 highest-priced books with their ratings.
  
2. Investigate correlations between book genres and prices.

Yearly Trends and Correlation:

3. Examine yearly trends in book releases to understand industry growth.
4. Explore correlations among numerical variables like book price, rating, and publication year.

Reviewers and Ratings Analysis:

5. Analyze the distribution of reviewer ratings, focusing on the percentage of verified reviewers.

6. Explore trends in average ratings over the years and examine common reviewer rating categories.

## Overview

This repository contains Python code for achieving the above objectives. The dataset includes information about the top 100 bestselling books on Amazon, covering a range of details like book titles, prices, ratings, authors, and customer reviews.


## Data Cleaning and Exploration

The analysis involves the use of Pandas, NumPy, Matplotlib, Seaborn, and Squarify libraries to clean, explore, and visualize the data.

### Data Cleaning

- Handling missing values in the 'rating' column.
- Removing rows with NaN values in the 'rating' column.
- Renaming the 'year of publication' column to 'year'.
- Optimizing data types for better memory usage.

### Data Exploration

- Descriptive statistics for book titles and customer reviews datasets.
- Yearly trends in the number of books released.
- Correlation analysis between different numerical features.

### Top 10 Highest Priced Books

Visual representation of the top 10 highest priced books, including the average price.

### Top 10 Highest Priced Books with Ratings

Comparison of the top 10 highest priced books with their ratings, including the average rating line.

### Top 5 Genres - Treemap

A treemap showing the distribution of the top 5 genres.

### Yearly Trends

Line chart illustrating the yearly trends in the number of books released.

### Correlation Heatmap

Heatmap displaying the correlation between different numerical features.

### Scatter Plot (Rating & Price)

Scatter plot to visualize the relationship between book price and rating.

### Jointplot

Jointplot for a better understanding of the relationship between book price and rating.

### Verified Reviewers Percentage

Pie chart representing the percentage of verified reviewers.

### Average Rating Over Years

Line chart showcasing the average rating of books over the years.

### Reviewer Rating Distribution

Pie chart illustrating the distribution of reviewer ratings.

## Conclusion

The analysis provides insights into the pricing, ratings, and trends of the top 100 bestselling books on Amazon. The visualizations help in understanding relationships and patterns within the dataset.


