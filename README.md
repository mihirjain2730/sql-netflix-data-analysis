# Netflix SQL Business Analysis

## Overview
This project analyzes Netflix Movies and TV Shows data using SQL to solve business problems and generate actionable insights from the dataset.

## Objectives

- Analyze the distribution of content types (movies vs TV shows).
- Identify the most common ratings for movies and TV shows.
- List and analyze content based on release years, countries, and durations.
- Explore and categorize content based on specific criteria and keywords.

## Dataset

Source: Netflix Dataset (Kaggle)

## Tech Stack

- SQL (PostgreSQL)
- Data Analysis
- Window Functions
- CTEs
- Aggregations
- String Functions

## Database Schema

```sql
netflix(
show_id,
type,
title,
director,
casts,
country,
date_added,
release_year,
rating,
duration,
listed_in,
description
)
```


## Business Problems Solved

1. Movies vs TV Shows count
2. Most common rating by content type
3. Movies released in a specific year
4. Top countries by content volume
5. Longest movie
6. Content added in last 5 years
7. Content by specific director
8. TV shows with more than 5 seasons
9. Content count by genre
10. India content release analysis
11. Documentary movies analysis
12. Content without director
13. Salman Khan movie analysis
14. Top actors in Indian content
15. Content categorization using keywords

## Key SQL Concepts Used

- CTE (WITH)
- Window Functions (RANK)
- GROUP BY
- Aggregations
- CASE Statements
- STRING Functions
- Date Functions

## Project Structure

```text
Netflix-SQL-Business-Analysis/
│
├── README.md
├── schema.sql
├── netflix_data_analysis.sql
├── netflix_titles.csv
└── screenshots/
```

## Results

This project demonstrates SQL problem-solving skills through business-focused analysis and data exploration.
