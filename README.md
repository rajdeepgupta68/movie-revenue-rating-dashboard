# 🎬 Movie Revenue & Ratings Dashboard

An end-to-end data analysis and visualization project built in Excel using the **TMDB 5000 Movies** dataset. This project demonstrates practical data analyst skills including data cleaning, analytical modelling, and interactive dashboard design.

![Dashboard Preview](images/Screenshot%202025-11-17%20155132.png)

---

## 📁 Project Files

| File | Description |
|---|---|
| `Movies_revenue_dashboard.xlsx` | Final interactive Excel dashboard |
| `tmdb_5000_movies.csv` | Original raw dataset |
| `cleaned_movies.csv` | Cleaned dataset exported from Power Query |
| `/images/` | Dashboard screenshots |

---

## 🔧 1. Data Cleaning - Power Query

All data preparation was handled inside **Power Query Editor**. Steps performed:

- Removed duplicate rows
- Filtered out movies with missing or invalid budget/revenue values
- Converted `budget` and `revenue` fields to numeric data types
- Extracted release year from date fields
- Cleaned null and zero values from ratings columns
- Trimmed and standardised genre and production company fields

**Calculated columns added:**

| Column | Formula |
|---|---|
| Profit | Revenue - Budget |
| ROI | Profit ÷ Budget |
| Budget Band | Categorised as Low / Medium / High / Blockbuster |

---

## 📊 2. Data Analysis - Pivot Tables & Formulas

Several PivotTables were built to explore the dataset from multiple angles:

- Average IMDb Rating by Year
- Studio (Production Company) Revenue
- Genre Revenue & Profitability
- ROI by Budget Band
- Top 10 Movies by Profit
- Budget vs IMDb Rating (filterable scatter plot using the `FILTER` function)

**Key Excel functions used:** `XLOOKUP`, `VLOOKUP`, `FILTER`, `IF`, `IFS`, and PivotTable Calculated Fields.

---

## 📈 3. Interactive Dashboard

The final dashboard brings all analyses together in a single, slicer-driven interface.

### Charts

- **Average IMDb Rating by Year** - Line Chart
- **Revenue by Studio** - Bar Chart
- **Genre Revenue Breakdown** - Column Chart
- **ROI by Budget Band** - Column Chart
- **Budget vs IMDb Rating** - Scatter Plot
- **Top 10 Movies by Profit** - Horizontal Bar Chart

### Slicers

Filter the entire dashboard by **Genre**, **Release Year**, **Budget Band**, and **Studio**.

---

## 💡 4. Key Insights

- **Higher budgets do not guarantee better ratings.** There is a sweet spot between **$20M–$60M** where IMDb ratings are consistently strong.
- **Animation and Adventure genres dominate ROI**, driven by wide audience appeal and long theatrical runs.
- **A small number of major studios generate the majority of total revenue**, reflecting significant market consolidation.
- **Certain low-budget films achieve exceptional ROI**, demonstrating strong profitability potential outside the blockbuster tier.

---

## 🛠️ 5. Tools Used

- Microsoft Excel - Power Query, PivotTables, Slicers, Charts
- Power Query Editor
- TMDB 5000 Movies Dataset
- Feature engineering and basic data modelling

---

## 🚀 6. How to Use

1. Download or clone this repository
2. Open `Movies_revenue_dashboard.xlsx` in Excel
3. Use the slicers to filter by genre, studio, budget band, or year
4. Interact with the charts to drill into movie performance trends

> **Note:** Ensure macros and data connections are enabled if prompted on first open.

---

## 👤 7. About This Project

This project was built to demonstrate core competencies expected of a junior data analyst, including:

- Data cleaning and transformation
- Analytical thinking and feature engineering
- Trend identification and pattern recognition
- Dashboard design and layout
- Storytelling with data

It serves as a portfolio piece showcasing the ability to take raw data from ingestion through to actionable insights using Excel as the primary tool.

---

## 📂 Dataset

**TMDB 5000 Movies Dataset** - sourced from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). Contains metadata on approximately 5,000 films including budget, revenue, genres, production companies, release dates, and audience ratings.
