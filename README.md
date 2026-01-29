# 📺 Netflix Dataset Analysis

## 📌 Project Overview

This project analyzes Netflix movies and TV shows data using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.
The goal is to explore content types, genres, countries, release trends, ratings, and duration through **comprehensive visualizations**.

---

## 📂 Dataset

**File:** `netflix_titles.csv`

**Columns include:**

* `show_id` – unique identifier
* `type` – Movie or TV Show
* `title` – title of content
* `director`
* `cast`
* `country`
* `date_added` – date added to Netflix
* `release_year`
* `rating`
* `duration` – minutes for movies / seasons for TV shows
* `listed_in` – genres
* `description`

---

## 🧰 Libraries Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔹 Data Cleaning Steps

1. Checked data shape, duplicates, missing values.
2. Filled missing categorical columns (`director`, `cast`, `country`, `rating`) with `'Unknown'`.
3. Converted `date_added` to **datetime** and replaced invalid/missing values with earliest date.
4. Cleaned `show_id` to integer values.
5. Extracted numerical `Duration` for Movies and TV Shows.
6. Created new columns: `Year_added`, `Month_added`.
7. Converted categorical columns to `category` type for easier analysis.
8. Ensured `Genres` column is ready for splitting and counting multiple genres.

---

## 📊 Visualizations

### 1️⃣ Content Type

* **Bar Plot & Pie Chart**: Movies vs TV Shows

### 2️⃣ Ratings

* **Countplot**: Distribution of content ratings

### 3️⃣ Country

* **Top 10 Countries**: Number of titles per country (Barplot)

### 4️⃣ Genres

* **Top 10 Genres**: Barplot after splitting multiple genres

### 5️⃣ Directors

* **Top 10 Directors**: Barplot

### 6️⃣ Cast

* **Top 10 Actors/Actresses**: Barplot after splitting multiple cast members

### 7️⃣ Date Added

* **Histogram by Year**: Number of titles added per year
* **Histogram by Month**: Number of titles added per month

### 8️⃣ Release Year

* **Histogram**: Distribution of release years

### 9️⃣ Duration

* **Movies**: Histogram of minutes
* **TV Shows**: Histogram of seasons

### 🔹 Advanced Visuals

* **Heatmap**: Ratings vs Content Type
* **Line Plot**: Titles added per year by type (Movie / TV Show)

---

## 🔹 Insights

* Majority of content are **Movies**.
* Most popular genres: **Dramas, Comedies, Documentaries, etc.**
* Top contributing countries: **United States, India, United Kingdom…**
* Peak content addition in recent years, showing Netflix growth.
* Ratings show wide variety with most content aimed at general audience.
* Movie durations mostly between 60–150 minutes; TV Shows mostly 1–5 seasons.


