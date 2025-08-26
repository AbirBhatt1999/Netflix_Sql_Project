# Netflix Movies and TV Shows Data Analysis using SQL
![Netflix Logo](https://github.com/AbirBhatt1999/Netflix_Sql_Project/blob/main/logo.png?raw=true)
## 📌 Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using **SQL**.  
The goal is to extract valuable insights and answer various business questions based on the dataset.  

The following README provides details about the **objectives, business problems, SQL solutions, findings, and conclusions**.

---

## 🎯 Objectives
- Analyze the distribution of content types (Movies vs TV Shows).  
- Identify the most common ratings for movies and TV shows.  
- List and analyze content based on release years, countries, and durations.  
- Explore and categorize content based on specific criteria and keywords.  

---

## 📂 Dataset
The data for this project is sourced from the Kaggle dataset:  
[Netflix Movies & TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🗂️ Schema
```sql
DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
