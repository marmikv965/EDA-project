#  Netflix Movies & TV Shows — Exploratory Data Analysis (EDA)

An in-depth Exploratory Data Analysis (EDA) of the Netflix dataset to uncover insights about content trends, genres, ratings, and countries.  
This project is designed to demonstrate my data analysis, visualization, and storytelling skills using Python.

---

##  Project Overview

Netflix has grown into one of the largest streaming platforms globally.  
The goal of this project is to **analyze the content available on Netflix** — movies and TV shows — to discover:

- Which type of content dominates the platform  
- How Netflix's content is distributed across countries  
- The most common ratings, genres, and release year trends  
- Insights that could help understand Netflix's global strategy

---

##  Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **Python** | Data analysis and visualization |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib** / **Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive analysis |
| **NumPy** | Data transformation |

---

##  Dataset

- **Source:** [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File Used:** `netflix_titles.csv`
- **Rows:** ~8,800  
- **Columns:** 12  
- **Key Columns:** `type`, `title`, `country`, `release_year`, `rating`, `listed_in`

---

##  Key Explorations & Insights

###  Movies vs TV Shows on Netflix
<p align="center">
  <img src="outputs/figures/movies_vs_shows.png" width="600">
</p>

>  **Insight:** Movies make up the majority of Netflix’s catalog, showing Netflix’s continued investment in film-based content.

---

###  Top 10 Countries with Most Netflix Titles
<p align="center">
  <img src="outputs/figures/top_10_countries_netflix_titles.png" width="600">
</p>

>  **Insight:** The **United States** and **India** dominate Netflix’s content library, highlighting their strong production industries.

---

###  Distribution of Ratings
<p align="center">
  <img src="outputs/figures/ratings_distribution.png" width="600">
</p>

>  **Insight:** Ratings like **TV-MA** and **TV-14** are the most frequent, indicating Netflix caters mainly to mature and teen audiences.

---

###  Content Growth Over the Years
<p align="center">
  <img src="outputs/figures/content_over_years.png" width="600">
</p>

>  **Insight:** Netflix’s content production has surged since **2015**, aligning with its global expansion and original content strategy.

---

