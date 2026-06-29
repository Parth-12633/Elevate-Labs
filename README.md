# 🎬 Netflix Movies & TV Shows Data Cleaning and Analysis

## 📌 Project Overview

This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas. The cleaned dataset is then analyzed through visualizations to gain insights into Netflix's content library.

This project was completed as part of a **Data Analyst Internship - Task 1 (Data Cleaning and Preprocessing).**

---

## 🎯 Objective

- Clean raw Netflix dataset
- Handle missing values
- Remove duplicate records
- Standardize data formats
- Convert date columns
- Prepare the dataset for analysis
- Perform basic exploratory data analysis (EDA)

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

Netflix Movies and TV Shows Dataset

---

## 🧹 Data Cleaning Steps

- Loaded the dataset using Pandas
- Checked dataset structure and data types
- Identified missing values
- Filled missing values in:
  - Director
  - Cast
  - Country
  - Rating
  - Duration
- Removed rows with missing Date Added values
- Removed duplicate records
- Standardized text values by removing extra spaces
- Converted `date_added` column into datetime format
- Renamed column names to lowercase with underscores
- Verified final data quality

---

## 📊 Visualizations

The following visualizations were created after data cleaning:

- Movies vs TV Shows
- Top 10 Countries with Most Netflix Content
- Netflix Content Added by Year
- Top 10 Genres
- Rating Distribution
- Movies vs TV Shows (Pie Chart)

---

## 📈 Key Insights

- Movies significantly outnumber TV Shows on Netflix.
- The United States contributes the highest amount of Netflix content.
- Netflix experienced rapid content growth after 2015.
- International Movies are among the most common genres.
- TV-MA is one of the most frequent content ratings.

---

## 📁 Project Structure

```
Netflix-Data-Cleaning/
│
├── netflix_titles.csv
├── netflix_titles_cleaned.csv
├── Netflix_Data_Cleaning.ipynb
├── README.md
│
└── screenshots/
    ├── movies_vs_tvshows.png
    ├── pie_chart.png
    ├── top10_countries.png
    ├── content_added_by_year.png
    ├── top10_genres.png
    └── rating_distribution.png
```

---

## 🚀 Outcome

The raw Netflix dataset was successfully cleaned and transformed into a structured dataset ready for analysis and visualization.

---

## 👨‍💻 Author

**Parth Gohil**