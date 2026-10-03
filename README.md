# 🎬 Netflix Content Analysis Using SQL

## 📌 Project Overview

This project analyzes the **Netflix titles dataset** using **MySQL** to explore the distribution, characteristics, and trends of movies and TV shows available on Netflix.

The project focuses on solving a set of **business-driven analytical questions using SQL**, ranging from basic aggregations to advanced SQL techniques such as **window functions, subqueries, string manipulation, date functions, CASE statements, and JSON_TABLE**.

The objective is to demonstrate how SQL can be used to transform raw entertainment data into meaningful insights.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the distribution of Movies and TV Shows on Netflix
- Identify the most common content ratings
- Analyze content by country
- Identify countries producing the most Netflix content
- Find the longest movies
- Analyze recently added content
- Identify directors with significant contributions
- Analyze TV Shows with multiple seasons
- Explore genre distribution
- Analyze Indian content on Netflix
- Identify documentary content
- Analyze missing director information
- Explore actors appearing in Netflix content
- Categorize Netflix content based on different attributes

---

## 🗂️ Dataset

The project uses the **Netflix Titles dataset** containing information about movies and TV shows available on Netflix.

### Dataset Features

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Type of content – Movie or TV Show |
| `title` | Name of the movie or TV show |
| `director` | Director(s) of the title |
| `cast` | Actors appearing in the title |
| `country` | Country/countries associated with the title |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating |
| `duration` | Movie duration or number of TV seasons |
| `listed_in` | Genre/category information |
| `description` | Description of the title |

---

## 🛠️ Tech Stack

- **MySQL**
- **SQL**
- **MySQL Workbench**
- CSV Dataset

### SQL Concepts Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `HAVING`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MAX()`
- `MIN()`
- `CASE`
- `JOIN`
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- `RANK()`
- String Functions
- `SUBSTRING_INDEX()`
- `CAST()`
- Date Functions
- `STR_TO_DATE()`
- `JSON_TABLE()`

---

## 📁 Project Structure

```text
Netflix_sql_project-main/
│
├── netflix_analysis.sql
├── netflix_titles.csv
├── README.md
└── Netflix logo.png
