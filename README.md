# Netflix Movie Data Analysis

This project performs an exploratory data analysis (EDA) on a Netflix movie dataset consisting of over 9800 movies. It includes genre frequency analysis, popularity insights, clustering, and sentiment analysis of movie descriptions.

---

## Dataset Overview

- **Total Entries**: 9827 movies
- **Columns**:
  - `Release_Date`
  - `Title`
  - `Overview`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average`
  - `Original_Language`
  - `Genre`
  - `Poster_Url`

---

## Preprocessing Summary

- No missing or duplicate values.
- `Release_Date` column was converted to extract the **year**.
- `Overview` and `Original_Language` were **excluded** from some analyses.
- Outliers were found in the `Popularity` column.
- `Genre` values (comma-separated) were cleaned, split into individual rows, and white spaces trimmed.

---

## Key Insights

- **Drama** is the most frequent genre, appearing in over **14%** of movies across 19 total genres.
- **Spider-Man: No Way Home** is the **most popular movie**, with genres: Action, Adventure, and Science Fiction.
- **United States vs Billie Holiday** and **Threads** are among the **least popular**.
- **Year 2020** had the **highest number of film releases** in the dataset.

---

## Visualizations

- **Bar Charts** for genre frequency and year-wise movie count.
- **Boxplots** to detect outliers in `Popularity` and `Vote_Average`.
- **Scatter Plots** to explore relationships between popularity and votes.

---
## K- Means Clustering

Movies were clustered into 4 groups based on:

- **Popularity**
- **Vote_Average**

Each cluster represents a group of movies with similar audience reception.
