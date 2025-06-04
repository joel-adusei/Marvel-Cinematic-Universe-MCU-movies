# Marvel-Cinematic-Universe-Movies- Database- project
This project demonstrates how to create and interact with a simple SQLite database using Python. It focuses on building a table to store information about Marvel Cinematic Universe (MCU) movies, inserting movie data, running SQL queries, and displaying results using Pandas.

# Project Overview
Database Name: MCU.db

Table Name: Movies

Purpose: Practice database operations like creating tables, inserting data, running SQL queries, and displaying results using Python and SQLite.

| Column Name | Data Type             | Description              |
| ----------- | --------------------- | ------------------------ |
| `movie_id`  | INTEGER (Primary Key) | Unique ID for each movie |
| `title`     | TEXT                  | Movie title              |
| `year`      | INTEGER               | Release year             |
| `score`     | REAL                  | IMDb rating              |

# Data Inserted
This project includes 22 MCU movies with their release year and IMDb scores.
Example entry:
(1001, 'Iron Man', 2008, 7.9)

# SQL Queries Used
SELECT score FROM MCU_Movies;
SELECT year, title FROM MCU_Movies ORDER BY year;
SELECT title, year FROM MCU_Movies ORDER BY score DESC;

# Final Output
After inserting and querying the data, the results are presented in a Pandas DataFrame for better visualization and analysis.


