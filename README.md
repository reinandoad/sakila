# sakila
# Sakila Database SQL Project

This project demonstrates SQL querying skills using the **Sakila Database**, a sample database representing a fictional DVD rental store. The dataset includes information about films, customers, rentals, actors, and payments. This project explores various SQL operations such as joins, aggregations, filtering, and subqueries to answer business-related questions.

## Project Objectives

- Strengthen SQL skills through real-world use cases
- Perform data exploration and analysis across multiple relational tables
- Demonstrate ability to write efficient and structured queries

## Dataset Overview

The Sakila database includes tables such as:

- `film`: Contains information about movies
- `actor`, `film_actor`: Contains actors and their roles in films
- `language`: Film languages
- `category`, `film_category`: Film genres
- `city`, `country`: Location data
- `payment`, `rental`: Transaction records

## Key Features

### 1. Data Retrieval
- Selected customer payment details including rental ID, amount, and payment date
- Retrieved 10 film titles starting with "S" with their release year and rental duration

### 2. Aggregation and Grouping
- Grouped films by rental duration to show film counts and average duration
- Calculated the highest replacement cost and lowest rental rate per film rating

### 3. Subqueries and Filtering
- Displayed films with above-average length
- Listed 10 films ending with 'h' and with a duration above average

### 4. Joins and Relational Queries
- Joined `film` and `language` to display movie titles, durations, and language where titles end with "K"
- Joined `film`, `film_actor`, and `actor` to show all films by a specific actor (actor_id = 14)
- Joined `film`, `film_category`, and `category` to count films per genre

### 5. Pattern Matching
- Filtered cities containing the letter "d" and ending with "a"
- Used `LIKE` statements to search for title patterns across different queries

Tools and Techniques
MySQL for running queries

Joins: INNER JOIN across multiple tables

Aggregation: COUNT, AVG, MAX, MIN, ROUND

Filtering: WHERE, LIKE, subqueries

Grouping and sorting: GROUP BY, ORDER BY, LIMIT

Purpose
This project was created as part of my portfolio to demonstrate practical SQL skills using a normalized relational database. It covers a range of common operations relevant to real-world business data.

File
Sakila.sql: Contains all SQL queries written for this project
