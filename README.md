# 📚 Amazon Top 50 Bestselling Books (2009–2019) — Excel Data Analysis Project

## 🧠 Project Overview
This project explores the **Amazon Top 50 Bestselling Books from 2009 to 2019** using **Microsoft Excel** to uncover patterns and insights related to book sales, authors, genres, prices, and ratings.  
The dataset includes information such as book title, author, user rating, number of reviews, price, year, and genre (Fiction or Non-Fiction).

The goal is to apply **data cleaning, analysis, and visualization** techniques in Excel to generate meaningful insights and prepare for portfolio demonstration.

---

## 🎯 Objectives
The analysis aims to answer the following key questions:

1. **Top 10 Authors** — Who appeared most frequently on the bestselling list?
2. **Highest Rated Year** — Which year had the highest average user rating?
3. **Top 10 Books by Reviews** — Which books received the most reviews?
4. **Average Price per Year** — How has the average book price changed over time?
5. **Price Distribution** — How are books distributed by price (Cheap / Mid / Expensive)?
6. **Genre Breakdown & Trend** — How do Fiction and Non-Fiction trends change across years?
7. **Correlations** — What is the relationship between:
   - Price and Reviews  
   - Rating and Reviews

---

## 🧩 Tools & Techniques Used
- **Microsoft Excel**
  - Data Cleaning (removing duplicates, formatting columns, handling missing data)
  - Pivot Tables for aggregation and analysis
  - IF statements for creating categories (e.g., Price Buckets)
  - Charts & Visualization (Bar, Line, Pie, and Scatter Charts)
  - Sorting, filtering, and summarizing large datasets

---
## 🧹 Data Preparation
1. Cleaned and formatted dataset (e.g., standardized author names and price format)
2. Added a **Price Category** column using:
   ```excel
   =IF([@Price]<10,"Cheap",IF([@Price]<=20,"Mid","Expensive"))

   ---

## 📈 Analysis & Insights

### 1. Top 10 Authors
- **Analysis:** Counted how many books each author published across years.by inserting pivot table
- **Insight:** A few authors (like Rick Riordan , Suzanne Collins and Gary Chapman appeared multiple times, showing consistent popularity.

### 2. Highest Average User Rating by Year
- **Analysis:** Calculated average rating per year using PivotTable.
- **Insight:** 2019 had the highest average rating, suggesting that this period had many well-received books.

### 3. Top 10 Books by Reviews
- **Analysis:** Ranked books by number of reviews.


### 4. Average Price per Year
- **Analysis:** Used PivotTable to compute average price for each year.
- **Insight:** Prices remained mostly stable, indicating consistent pricing strategy over the decade.

### 5. Price Distribution
- **Analysis:** Created “Cheap,” “Mid,” and “Expensive” price categories using an IF formula.
- **Insight:** Majority of books fall under the Mid-price range with 45.86%,followed by the Cheap on 42.48 and the Expensive one was of 11.65% which shows the affordability of the books

### 6. Genre Breakdown
- **Analysis:** Compared counts of Fiction vs. Non-Fiction per year.
- **Insight:** Fiction dominated most years, but Non-Fiction gained traction in the late 2010s.


