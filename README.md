# Indian Startup Funding Analysis — Power BI Dashboard

## 📌 Project Overview
This project analyzes Indian startup funding data to uncover trends across cities, industries, and years. Built using Power BI Desktop, it visualizes funding patterns to help understand which cities and sectors attract the most investment.

# Dataset
- **Source:** [Indian Startup Funding dataset](https://www.kaggle.com/) by SRK (Kaggle)
- **Fields used:** City, Industry, Amount (USD), Date, Startup Name, Investors

# Data Cleaning
Before visualization, the raw dataset required cleaning:
- Merged inconsistent city name spellings (e.g., "Bengaluru" / "Bangalore", "New Delhi" / "Delhi")
- Removed comma separators from the `Amount in USD` column and fixed data type errors (converted to numeric)
- Converted the `Date` column to a proper Date data type for time-based analysis
- Handled missing/null values in key columns

# Dashboard Visuals
1. **City-wise Funding (Bar Chart)**s — Shows total funding received by each city, highlighting startup hubs.
2. **Industry-wise Funding (Donut Chart)** — Breaks down funding share by industry/sector.
3. **Yearly Funding Trend (Line Chart)** — Tracks how total funding has evolved over time.

# Key Insights
- **Bangalore** dominates as India's top startup funding hub, receiving significantly more funding (~₹20bn+) than any other city, followed by Mumbai, New Delhi, and Gurgaon
- **Ecommerce** (19.47%) and **Consumer Internet** (16.98%) are the top two industry verticals by funding share, together accounting for over a third of total startup funding
- The total funding tracked across the dataset stands at **₹37bn**, spread across multiple industries and 40+ cities
- Yearly funding trend (2015–2020) shows high volatility, with major peaks around **2017** and **2019**, and a sharp decline going into **2020**

# Tools Used
- Power BI Desktop
- Excel/CSV (initial data inspection)

# Files in this Repo
- `startup_funding.pbix` — Power BI dashboard file
- `raw_data.csv` — Original dataset
- `cleaned_data.csv` — Cleaned dataset (if exported separately)

# What I Learned
Learned how to clean messy real-world data — handling inconsistent city name spellings, fixing incorrect data types, and formatting dates before building visuals. Also practiced structuring a multi-chart Power BI dashboard with filters (Industry Vertical, Date) to make the report interactive and easy to explore.

---
 Feel free to connect on [LinkedIn] or check my other projects on [GitHub].
