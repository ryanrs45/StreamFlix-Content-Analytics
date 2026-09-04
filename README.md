# StreamFlix Content Analytics

An end-to-end data analytics project using **Python, Pandas, SQL, Jupyter Notebook, and Power BI** to analyze subscriber behaviour, viewing trends, content performance, customer experience, and catalogue investment.

---

## Project Overview

StreamFlix is a fictional streaming platform dataset containing subscriber, content, viewing, rating, review, and watchlist information.

The objective of this project was to transform raw data into actionable business insights through:

- Data cleaning and validation
- Exploratory Data Analysis (EDA)
- KPI calculation
- Data visualization
- Power BI dashboard development
- Management reporting

The analysis covers approximately **979,000 records across 6 interconnected datasets**.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- SQL
- Power BI
- Microsoft Excel

---

## Dataset Structure

The project uses six datasets:

| Dataset | Records | Description |
|---|---:|---|
| Subscribers | 15,000 | Subscriber demographics, plans, pricing, churn and activity |
| Titles | 9,000 | Movies and TV Shows available on StreamFlix |
| Watch History | 650,000 | Individual viewing sessions |
| Ratings | 130,000 | User star ratings |
| Reviews | 110,000 | Written reviews and sentiment |
| Watchlist | 65,000 | Titles saved to subscriber watchlists |

---

## Project Workflow

### Phase 1 — Data Cleaning

Performed data quality checks including:

- Missing value analysis
- Duplicate detection
- Data type conversion
- Date validation
- Primary key validation
- Foreign key validation
- Business rule checks
- Completion percentage validation

The cleaned datasets were prepared for analysis and dashboard development.

---

### Phase 2 — Exploratory Data Analysis

Created 10 visualizations:

1. Monthly Viewing Volume
2. Monthly Watch Hours Trend
3. Watch Hours by Genre
4. Movies vs TV Shows Split
5. Top Countries by Watch Hours
6. Subscriber Plan Distribution
7. Device Usage
8. Subscriber Age Distribution
9. Completion Rate by Genre
10. Review Sentiment Breakdown

---

## Key Business KPIs

| KPI | Result |
|---|---:|
| Total Watch Hours | 3.33M |
| Active Subscriber Rate | 74.66% |
| Churn Rate | 25.34% |
| Average Completion Rate | 65.31% |
| Monthly Recurring Revenue | $175,868.51 |
| ARPU | $15.70 |
| Avg. Watch Time per Active Subscriber | 297.66 hours |
| Watchlist Conversion Rate | 46.23% |
| Hit Concentration | 30.99% |
| Originals Share of Watch Hours | 27.17% |

---

## Key Insights

- **Drama** generates the highest watch hours, followed by Comedy and Action.
- **TV Shows contribute approximately 86.47% of total watch hours**, compared with 13.53% for Movies.
- The **United States** generates the highest watch hours, followed by India and the United Kingdom.
- **Smart TV** is the most-used viewing device, followed by Mobile.
- **68.19% of written reviews are Positive**, while 11.12% are Negative.
- **4-star ratings** are the most common rating.
- StreamFlix Originals represent **21.84% of the catalogue** but contribute **27.17% of total watch hours**.
- Animation provides the strongest watch-hours-per-$1,000 content spend among the analysed genres.
- Several licensed titles are approaching expiry, creating opportunities to prioritize renewals based on cost and content performance.

---

## Power BI Dashboard

A five-page interactive Power BI dashboard was developed.

### Dashboard Pages

1. Engagement Overview
2. Content Performance
3. Subscriber Insights
4. Experience
5. Catalogue & Investment

The dashboard includes KPIs, trend analysis, content performance metrics, subscriber segmentation, customer sentiment, device usage, and investment efficiency.

---

## Project Structure

```text
StreamFlix-Content-Analytics
│
├── charts
│   └── 10 EDA visualizations
│
├── dashboard
│   └── Phase4_Dashboard_Hemanth.pbix
│
├── documents
│   ├── Data Dictionary
│   ├── ERD
│   ├── Project Requirements
│   └── SQL queries
│
├── notebooks
│   ├── Phase1_DataCleaning_Hemanth.ipynb
│   ├── Phase2_EDA_Hemanth.ipynb
│   └── Phase3_KPIs_Hemanth.ipynb
│
├── reports
│   ├── Phase3_KPI_Summary_Hemanth.csv
│   └── Phase4_Report_Hemanth.docx
│
└── README.md
```
## Data Availability

The full raw and cleaned datasets are not included in this repository because of file-size considerations.

The notebooks, visualizations, dashboard, documentation, KPI summary, and management report are provided to demonstrate the complete analytical workflow.

---

## Author

**Hemanth**

Aspiring Data Engineer / Data Analyst

Skills demonstrated in this project:

`Python` `Pandas` `SQL` `Power BI` `EDA` `Data Cleaning` `Data Visualization` `Business Intelligence`