# Goodreads Book Data Analysis 📚

## Overview

This repository contains a data analysis project focused on exploring a dataset of books, sourced from Goodreads. The goal of this project is to uncover interesting patterns, trends, and insights within the book data. This could involve analyzing authors and publication.

This project serves as a portfolio piece demonstrating skills in data analysis and visualization using Python. The complete analysis code, performed within a Google colabs Notebook environment, is included in this repository.

## Key Visualisations 

The project aims to create insightful visualizations

* **Distribution of Books by Genre:** A bar chart or pie chart showing Books with most occurrences (using Matplotlib & Seaborn).
* **Top 10 most-rated books:** A bar chart highlighting Top 10 most-rated books
* **Distribution of Average Ratings** A box plot comparing the Distribution of Average Ratings (using Matplotlib & Seaborn).
* **Number of Books Published Over Time** This line graph shows the trend of book publications over time, which can reveal changes in publishing patterns and potentially identify popular periods for specific genres. (using Matplotlib & Plotly).
* **Top 10 Books with Most Text Reviews:** This bar chart highlights the books that have received the most text reviews, indicating which books have generated the most discussion and user engagement. (using Matplotlib & Plotly).


## Source

Data is sourced from the `cleanedbooks.csv` file provided by the user.


## Key Variables

* Title
* Author
* Genre
* Publication Year
* Average Rating
* Number of Ratings
* Number of Reviews
* ISBN
* Publisher

## Methodology & Tools

The analysis was conducted using Python within a Googel Colab Notebook environment. Key steps included:

1.  **Data Loading & Cleaning:** Importing the `cleanedbooks.csv` dataset using Pandas, handling missing values, and ensuring data consistency.
2.  **Exploratory Data Analysis (EDA):** Examining the distribution of key variables, identifying potential outliers, and looking for initial patterns and relationships using Pandas.
3.  **Visualization:** Creating insightful plots using Matplotlib, Seaborn, and/or Plotly to understand the data and communicate findings.

**Main Libraries:**

* **Python:** pandas
* **Python (Visualization):** matplotlib, seaborn, plotly

## Key Findings & Insights (To be populated after analysis)
1. Top 10 Most Occurring Books:

Insight: This bar chart highlights the books that appear most frequently in the dataset. This might be due to different editions or versions of the same book.
Implication: Ensure that you handle different editions correctly to avoid redundancy in your recommendations. This information can also be used to identify classic or highly-republished books.

2. Top 10 Authors with Most Books:

Insight: This bar chart shows the authors who have published the most books in the dataset.
Implication: Recommend books by popular authors as they tend to have a wider readership. Consider creating author-specific recommendations or highlighting their new releases.


3. Average Rating by Genres (Top 10):

Insight: This bar chart shows the average ratings for the top 10 most frequent genres. Some genres, like "Sequential Art" or "Historical", tend to have slightly higher average ratings than others, like "Fiction" or "Young Adult".
Implication: You can use this information to personalize recommendations based on user genre preferences. For example, if a user prefers "Sequential Art", recommend books with higher average ratings within that genre.

4. Number of Books Published Over Time:

Insight: This line graph shows a general increase in the number of books published over time, with potential fluctuations or spikes in certain years.
Implication: This trend analysis can help identify publishing patterns, understand popular periods for specific genres, and potentially forecast future book releases.

5. Distribution of Text Reviews Count:

Insight: This histogram reveals that the majority of books have a relatively low number of text reviews, with a long tail of books having a higher number of reviews. This indicates that user engagement through text reviews is concentrated on a smaller subset of books.
Implication: Encourage users to write more text reviews by implementing incentives or highlighting books with fewer reviews. This would provide more comprehensive data for analysis and recommendations.

6. Top 10 Books with Most Text Reviews:

Insight: This bar chart identifies the books that have generated the most discussion and user engagement through text reviews.
Implication: Use this information to feature popular and highly-discussed books on your platform. Consider incorporating text review data into your recommendation algorithm to personalize suggestions based on user interests.


## Limitations & Future Work

* **Data Scope:** The analysis is limited to the data available in the `cleanedbooks.csv` file.
* **Potential Biases:** The dataset might reflect biases present in the data source which is Goodreads.
* **Further Exploration:** Future work could involve:
    * Incorporating additional book-related datasets.
    * Performing sentiment analysis on book reviews (if available).
    * Building predictive models (e.g., predicting book ratings).
    * Exploring network analysis of authors or genres.
