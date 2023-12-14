# Top 100 Bestselling Book Reviews on Amazon - Data Analysis and Visualization

**Overview:**

This repository contains Python scripts for analyzing and visualizing data related to the top 100 bestselling book reviews on Amazon. The dataset includes information about book titles, customer reviews, book prices, ratings, authors, publication years, genres, and more.

**Dataset:**

The dataset consists of two CSV files:

**book_titles.csv:** Contains details about book titles, prices, ratings, authors, publication years, genres, and URLs.
**customer_reviews.csv:** Includes information on customer reviews, reviewers, review titles, ratings, review descriptions, verification status, dates, and ASIN.

# Data Analysis and Visualization
**Data Exploration**

Imported necessary libraries: Pandas, NumPy, Matplotlib, Seaborn.

Loaded two CSV files into Pandas DataFrames (book_titles and customer_reviews).

Explored the structure and summary statistics of the datasets to gain insights into the data distribution.

**Data Cleaning**

Removed rows with missing values in the 'rating' column from book_titles dataset.

Renamed the 'year of publication' column to 'year' in the book_titles dataset for better clarity.

Converted data types to optimize memory usage (Rank and year columns to int16).

**Data Visualization**

Visualized the top 10 highest priced books and their ratings.

Explored yearly trends in the number of books released over time.

Investigated the correlation between book price, rating, and year using heatmaps and scatter plots.

Analyzed reviewer ratings and percentages of verified reviewers.

**Insights**

Most books were published after 2010, with the highest number released in 2023.

There are only 3 book above average price. Out of that 3 books 2 book consists several series.

6 out of 10 Top highest priced books are above average rating

TOP Genres are respective: Children, literature, Nonfiction, Fantasy, Memoir.

99% of reviewers are verified.

Newly released books struggled to have more than average rating.

The relationship between book price and rating seems inconclusive, showing no strong correlation.

Most of the ratings are either 4 or 5.

**Conclusion**

This repository showcases data analysis and visualization techniques applied to the top 100 bestselling book reviews dataset from Amazon. The Python scripts demonstrate exploration, cleaning, and visualization methods to extract insights and trends from the data.
