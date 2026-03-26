# End-to-End Data Analysis: Largest Companies in India

## Overview

This project performs an end-to-end data analysis of the largest companies in India by scraping data from Wikipedia and transforming it into actionable insights. It covers the complete data pipeline including data collection, cleaning, analysis, and visualization.

---

## Objective

To analyze the financial performance and industry distribution of top Indian companies using real-world data.

---

## Tech Stack

* Python
* BeautifulSoup (Web Scraping)
* Pandas (Data Cleaning & Analysis)
* Matplotlib (Data Visualization)

---

## Workflow

1. **Web Scraping**

   * Extracted company data from Wikipedia using BeautifulSoup

2. **Data Cleaning**

   * Removed special characters and converted financial columns to numeric format
   * Handled missing values and ensured consistency

3. **Exploratory Data Analysis (EDA)**

   * Identified top companies by revenue
   * Analyzed industry distribution
   * Examined relationships between financial metrics

4. **Advanced Analysis**

   * Calculated **Profit Margin** to measure company efficiency
   * Evaluated **Asset Turnover Ratio** to assess asset utilization
   * Performed **Industry-level aggregation** for sector insights

5. **Data Visualization**

   * Top 10 companies by revenue
   * Industry distribution
   * Revenue vs Profit relationship
   * Profit margin and asset efficiency comparisons

---

## Key Insights

* A small number of companies dominate overall revenue, indicating market concentration
* Energy and financial sectors are highly represented among top companies
* Strong positive correlation exists between revenue and profit
* Some companies generate high revenue but relatively low profit margins
* Asset efficiency varies significantly across industries

---

## Output

* Cleaned dataset: `largest_companies_in_india.csv`
* Analysis notebook: `analysis.ipynb`

---

## ▶ How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```
   jupyter notebook analysis.ipynb
   ```



## Learnings

* Real-world web scraping and handling structured HTML data
* Data cleaning and preprocessing using Pandas
* Performing exploratory and advanced data analysis
* Generating business insights from raw data
* Creating meaningful visualizations


## Future Improvements

* Automate data updates using APIs
* Build an interactive dashboard (Power BI / Tableau)
* Extend analysis with time-series or multi-year data
