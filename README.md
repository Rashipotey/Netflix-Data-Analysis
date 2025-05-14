# Netflix Movie Data Analysis

This project explores a dataset of 9,800+ movies available on Netflix to extract meaningful insights related to genres, popularity, and yearly trends. It involves cleaning, preprocessing, and analyzing data to identify the most popular movies, most frequent genres, and active release years.

---

## Dataset Summary

- **Rows**: 9827  
- **Columns**: 9  
- **Missing Values**: None  
- **Duplicates**: None  

### Columns:
| Column             | Description                         |
|--------------------|-------------------------------------|
| `Release_Date`     | Movie release date                  |
| `Title`            | Movie title                         |
| `Overview`         | Description/summary (dropped)       |
| `Popularity`       | Popularity score                    |
| `Vote_Count`       | Total vote count                    |
| `Vote_Average`     | Average rating                      |
| `Original_Language`| Original language (dropped)         |
| `Genre`            | Comma-separated genre list          |
| `Poster_Url`       | Poster image URL (not analyzed)     |

---

## Data Preprocessing

- `Release_Date` converted to datetime and year extracted.
- `Original_Language` and `Overview` columns dropped.
- `Genre` cleaned by splitting comma-separated strings and stripping white spaces.
- `Popularity` column contains outliers.
- No missing or duplicate values.
