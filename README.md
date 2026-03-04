# aneesmiftha.github.io
"Portfolio website of Anees Miftha — SQL, Tableau, Data Analytics"
# Cyclistic Bike-Share Analysis Case Study
**Tools Used:** SQL (Google BigQuery), Python, Tableau, Google Sheets

## 1. Project Overview
The goal of this analysis is to understand how annual members and casual riders use Cyclistic bikes differently. These insights will help design a marketing strategy to convert casual riders into long-term annual members.

## 2. Data Processing & Cleaning
I analyzed 12 months of historical trip data (March 2023 - February 2024). 
* **Handling Large Data:** Used **Python** to chunk large CSV files that exceeded the 100MB BigQuery upload limit.
* **Data Integrity:** Removed over **500,000 duplicate rows** and filtered out "test" rides (under 1 minute).
* **Final Dataset:** 5,707,365 clean rows were used for the final analysis.

## 3. Key Insights
* **Ride Duration:** Casual riders spend significantly more time per ride (~21 mins) compared to members (~12 mins).
* **Usage Patterns:** Members use bikes consistently during the week (commuter behavior), while casual riders peak on weekends (leisure behavior).
* **Seasonality:** Peak activity occurs between June and August.

## 4. Business Recommendations
* **Weekend Specials:** Target casual riders with weekend-only membership passes.
* **Seasonal Discounts:** Offer summer conversion "early bird" discounts in May.
* **Digital Marketing:** Focus ad campaigns at the top 5 "Casual" start stations (waterfront/tourist areas).

## 5. Visualizations
[Link to my Interactive Tableau Dashboard](PASTE_YOUR_TABLEAU_LINK_HERE)
