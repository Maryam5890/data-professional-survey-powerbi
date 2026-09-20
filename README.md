## Data Professional Survey Dashboard (Power BI)

An interactive Power BI dashboard analyzing survey responses from **630 data professionals** worldwide, exploring career paths, salaries, job satisfaction, and demographics in the data industry. Built as a hands-on practice project to strengthen my Power BI skills.

## What it covers
- Breakdown of respondents by country and gender
- Average salary by gender and by job title
- Job satisfaction ratings: work/life balance and salary satisfaction
- Average age of respondents
- Favorite programming languages among data professionals
- Career path breakdown by current role (Data Analyst, Data Engineer, Data Scientist, etc.)

## Tools used
- Power BI Desktop (data modeling, DAX measures, interactive visuals)
- Power Query (data cleaning and transformation)
- Excel (initial data review)

## Data cleaning
The raw survey data (included in this repo) was cleaned and transformed using Power Query within Power BI — including handling blanks, standardizing inconsistent categories (e.g. merging "SQL" and "Sql" entries), and preparing fields for analysis. All transformation steps are visible in the `.pbix` file under **Transform Data**.

## Files in this repo
- `power_bi_full_project.pbix` — the full interactive Power BI report, including Power Query cleaning steps
- `Data Professional Survey.xlsx` — the raw, uncleaned survey dataset
- `assets/` — dashboard screenshots

## Preview
![Dashboard Screenshot](assets/dashboard-overview.png)

## Key insights
- **Python is the clear favorite language** among respondents, far ahead of R and SQL.
- **Data Analyst is the most common role** in the survey, making up the majority of respondents — followed by Data Engineers and Data Scientists.
- The **United States** accounts for the largest share of respondents, with India, the UK, and Canada also well represented.
- Respondents rated their **work/life balance (5.74/10) noticeably higher than their salary satisfaction (4.27/10)** — suggesting people are more content with their day-to-day work than with what they're paid for it.
- **Average salary was fairly close between male and female respondents**, though a closer look at the breakdown highlights where gaps still exist.
- The average survey taker was about **30 years old**.

