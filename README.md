# Bike-Sales-Data-Analysis-Project.
An interactive Excel dashboard analysing bike buyer demographics, income levels and purchasing trends. 

## Project Overview
This project focuses on cleaning, analyzing, and visualizing a demographic dataset of bike buyers to uncover consumer purchasing trends. Using Microsoft Excel, I transformed a raw dataset into an interactive executive dashboard that allows stakeholders to filter key metrics by region, education level, and marital status on the fly.

## Key Insights Discovered
* **Income Influence:** Individuals with higher average income levels are more likely to purchase a bicycle, across both male and female demographics.
* **Commute Distance Impact:** Customers with shorter commutes (0–1 miles) have the highest conversion rate, whereas those commuting 10+ miles are significantly less likely to buy a bike.
* **Age Group Trends:** The "Middle Age" bracket (ages 31–54) constitutes the primary consumer base for bike purchases compared to adolescents and seniors.

## Data Cleaning & Transformation Process
Before building the dashboard, the raw data required comprehensive restructuring and cleaning:
* **Duplicate Removal:** Identified and eliminated duplicate rows to ensure data integrity.
* **Regional Optimization:** Adjusted syntax architecture to align with local system formatting parameters (utilizing semicolon list separators rather than standard commas).
* **Advanced Logic & Categorization:** Implemented complex nested conditional statements (`=IF(...)`) to group continuous age numbers into discrete, logical cohorts (*Adolescent*, *Middle Age*, *Old*).
* **Alphabetical Sort Overrides:** Resolved Excel's standard string sorting bug by manually re-ordering the "10+ Miles" commute distance metric into its true chronological sequence.

## Features Implemented
* **Dynamic Pivot Tables:** Engineered deep-dive summaries analyzing income variations, commute hurdles, and age demographics against historical purchase behavior.
* **Executive Dashboard:** Built an interactive reporting pane combining formatted currency charts (Bar and Line graphs).
* **Interactive Slicers:** Connected global slicers for *Region*, *Education*, and *Marital Status* to allow for cross-functional reporting across all charts simultaneously.

## How to View the Project
1. Download the `Excel Project Dataset.xlsx` file from this repository.
2. Open it in Microsoft Excel.
3. Navigate to the **Dashboard** tab to interact with the visualizations and slicers.
