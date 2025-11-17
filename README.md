🎬 Movie Revenue & Ratings Dashboard (Excel Project)
-
An end-to-end data analysis & visualization project built in Excel using the TMDB 5000 Movies dataset.
This project demonstrates skills in Power Query, data cleaning, pivot tables, VLOOKUP/XLOOKUP, DAX-style calculations, data modeling, interactive dashboards, and storytelling with analytics.

📁 Project Files
-
Movies_revenue_dashboard.xlsx	Final interactive Excel dashboard 

tmdb_5000_movies.csv	Original dataset

cleaned_movies.csv	Cleaned dataset exported from Power Query

/images/	Dashboard screenshots

**1. Data Cleaning (Power Query)**
-
Steps performed in Power Query:

Removed duplicate rows

Filtered out movies with missing or invalid budget/revenue

Converted data types (budget, revenue → number)

Extracted release year

Created calculated columns:

Profit = Revenue − Budget

ROI = Profit ÷ Budget

Budget Band (Low, Medium, High, Blockbuster)

Cleaned null or zero values for ratings

Trimmed and transformed genre & production company fields

📊 2. Data Analysis (Pivot Tables & Formulas)
-
Created several PivotTables to analyze:

Average IMDb Rating by Year

Studio (Production Company) Revenue

Genre Revenue & Profitability

ROI by Budget Band

Top 10 Movies by Profit

Budget vs IMDb Rating (Filterable scatter plot using FILTER function)

Key Excel functions used:

XLOOKUP

VLOOKUP

FILTER

IF & IFS

PivotTable Calculated Fields

📈 3. Interactive Dashboard
-
The final dashboard includes:

**📊 Charts**

Average IMDb Rating by Year (Line Chart)

Revenue by Studio (Bar Chart)

Genre Revenue Breakdown (Column Chart)

ROI by Budget Band (Column Chart)

Budget vs IMDb Rating (Scatter Plot)

Top 10 Movies by Profit (Horizontal Bar Chart)

**🎛 Slicers**

Genre

Release Year

Budget Band

Studio

🔍 4. Key Insights
-
Some insights discovered:

Higher budgets do not guarantee better IMDb ratings — but there is a sweet spot between $20M–$60M where ratings are consistently strong.

Animation & Adventure genres dominate ROI due to high audience appeal and long theatrical runs.

A few major studios contribute to the majority of revenue, highlighting market consolidation.

Certain low-budget films achieve exceptional ROI, showing strong profitability potential outside blockbusters.

🛠 5. Tools Used
-
Excel (Power Query, PivotTables, Slicers, Charts)

Power Query Editor

TMDB 5000 Movies Dataset

Basic Data Modeling & Feature Engineering

📸 Dashboard Preview



📌 6. How to Use This Project
-
Download the repo

Open Movies_revenue_dashboard.xlsx

Use slicers to explore genre, studio, budget, and year trends

Interact with charts to drill into movie performance

👨‍💻 7. About This Project
-
This project demonstrates core skills required for junior data analyst roles, including:

Data cleaning

Analytical thinking

Trend identification

Dashboard design

Storytelling with data

Excel automation
