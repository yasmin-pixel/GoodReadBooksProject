# 📚 Goodreads Book Analysis Project

Welcome to my final project for the data analytics bootcamp! This project demonstrates my skills in data analysis, visualization, and storytelling through data. I utilized both **Tableau** and **Google Colab** (Python) to explore, clean, and visualize a dataset from Goodreads, showcasing trends and insights in reader preferences and book performance.

---
# Project Scenario

I'm a data analyst at a book recommendation platform, working with a Goodreads dataset to:

- Understand reader preferences 

- Analyze trends 

- Improve recommendation systems

## 🚀 Key Skills Used

- **Python Programming**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** for visualizations
- **Tableau** for interactive dashboards
- **Data Cleaning** and preprocessing
- **Exploratory Data Analysis (EDA)**
- **Data Storytelling** and presentation

---

## 🧠 Project Overview

The project is based on a dataset of books from [Goodreads](https://www.goodreads.com/). Using the `cleanedbook.csv` dataset, I conducted a comprehensive analysis using Python in Google Colab and created a dynamic Tableau dashboard to visualize key trends and metrics.

---

## 🔍 Objectives

- Analyze top-rated books by genre, author, and average ratings
- Understand distribution patterns in book ratings, page counts, and review volumes
- Visualize correlations between features like rating and number of reviews
- Create an interactive dashboard for dynamic data exploration

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                 |
|----------------|------------------------------------------|
| **Python**     | Data wrangling and analysis              |
| **Pandas**     | Data manipulation                        |
| **NumPy**      | Numerical computation                    |
| **Matplotlib** | Static visualizations                    |
| **Tableau**    | Interactive data visualization dashboard |

---

## 📁 Files in This Repository

- `cleanedbook.csv` — Preprocessed book dataset used in both projects
- `GoodReadBook.ipynb` — Python notebook (Google Colab) containing data cleaning, EDA, and visualizations
- `finalprojectGoodreadTableau.twbx` — Tableau workbook with interactive dashboard
- `README.md` — Overview of the project (this file)

---

## 📊 Tableau Dashboard

The Tableau dashboard provides an intuitive way to explore:

- Top 10 books by rating and review count
- Author analysis by number of books and average rating
- Book popularity trends

📎 **To view the dashboard**, open `finalprojectGoodreadTableau.twbx` using Tableau Desktop or Tableau Public.

![image](https://github.com/user-attachments/assets/fd23a5c8-5684-49c9-87c1-d41fa822f441)

## Key Visualisations using Google Colabs 

The project aims to create insightful visualizations

 Top 10 Most Occuring Books: A bar chart highlighting Top 10 most- Occuring Books
  
 ![image](https://github.com/user-attachments/assets/b0306965-1a52-4fc4-b2f4-92e66c9ffc27)

 **Top 10 most-rated books:** A bar chart highlighting Top 10 most-rated books
  
![image](https://github.com/user-attachments/assets/639aa6d9-a2ef-4bea-b1d3-2da0eb3554c2)

 **Distribution of Average Ratings** A box plot comparing the Distribution of Average Ratings (using Matplotlib & Seaborn
  
  ![image](https://github.com/user-attachments/assets/7898f447-bb76-4ae9-b49e-59bb4f49393c)

 **Number of Books Published Over Time** This line graph shows the trend of book publications over time, which can reveal changes in publishing patterns and potentially identify popular periods for specific genres. (using Matplotlib & Plotly).
  
  ![image](https://github.com/user-attachments/assets/63eaed48-ef44-4e03-8fb8-854719f7822d)

 **Top 10 Books with Most Text Reviews:** This bar chart highlights the books that have received the most text reviews, indicating which books have generated the most discussion and user engagement. (using Matplotlib & Plotly).
  
  ![image](https://github.com/user-attachments/assets/e6bf875f-398b-4f90-8162-9570becfaf44)

## Source

Data is sourced from the `cleanedbooks.csv` file provided by the user.

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

2. Top 10 Authors with Most Books:

Insight: This bar chart shows the authors who have published the most books in the dataset.

3. Number of Books Published Over Time:

Insight: This line graph shows a general increase in the number of books published over time, with potential fluctuations or spikes in certain years.

4. Distribution of Text Reviews Count:

Insight: This histogram reveals that the majority of books have a relatively low number of text reviews, with a long tail of books having a higher number of reviews. This indicates that user engagement through text reviews is concentrated on a smaller subset of books.

5. Top 10 Books with Most Text Reviews:

Insight: This bar chart identifies the books that have generated the most discussion and user engagement through text reviews.

## Limitations & Future Work

* **Data Scope:** The analysis is limited to the data available in the `cleanedbooks.csv` file.
* **Potential Biases:** The dataset might reflect biases present in the data source which is Goodreads.
* **Further Exploration:** Future work could involve:
    * Incorporating additional book-related datasets.
    * Performing sentiment analysis on book reviews (if available).
    * Building predictive models (e.g., predicting book ratings).
    * Exploring network analysis of authors or genres.
