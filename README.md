# Netflix Content Analysis — Excel Dashboard

## Project Overview
Analyzed Netflix's content library of 8,808 titles to understand 
trends in content type, country distribution, ratings and 
yearly growth patterns.

## Tools Used
- Microsoft Excel
- Pivot Tables
- Charts and Dashboard
- Data Cleaning Formulas

## Dataset
- Source: Kaggle — Netflix Movies and TV Shows
- Link: https://www.kaggle.com/datasets/shivamb/netflix-shows
- Rows: 8,808
- Columns: 12

## Data Quality Issues Found
- Country column had multiple countries per cell → extracted primary country
- Date column stored as text → extracted year using RIGHT() formula
- 831 blank values in country column → left as blank
- Listed_in column had multiple genres → extracted primary genre
- Duration column had mixed units (min/Season) → split into two columns

## Business Questions Answered
1. How many total titles are on Netflix?
2. What is the Movies vs TV Shows split?
3. Which are the top 10 countries by number of titles?
4. Which year had the most titles added?
5. What is the most common content rating?
6. What are the top genres on Netflix?
7. What is the average movie duration?
8. How many titles were added after 2019?

## Key Findings
- Total titles: 8,808
- Movies make up 70% of content
- USA is the top country with 3211 titles
- Netflix added most content in 2019
- Most common rating is TV-MA


## Files in this Repository
| File | Description |
|---|---|
| netflix_titles.csv | Raw original dataset |
| Netflix_Analysis.xlsx | Cleaned workbook with dashboard |
| Data_Quality_Report.pdf | 1 page data quality findings |
| screenshots/dashboard.png | Dashboard preview image |
