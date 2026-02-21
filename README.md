
# IPL Data Analytics Dashboard (2008–2022) | Power BI Project

##  Introduction

The Indian Premier League (IPL) is one of the most popular T20 cricket leagues in the world. This project analyzes IPL data from **2008 to 2022** to generate meaningful insights about team performance, player statistics, match outcomes, and season trends using **Power BI**.

The goal of this project is to transform raw IPL match and ball-by-ball data into an interactive dashboard for analytical decision-making and performance evaluation.


## Objectives

* Analyze team performance across all IPL seasons (2008–2022)
* Identify top-performing batsmen and bowlers
* Evaluate toss impact on match results
* Analyze venue-based winning patterns
* Compare season-wise trends in total runs and matches
* Build an interactive Power BI dashboard


## 📂 Dataset Description

The dataset contains two main CSV files:

### 1️⃣ matches.csv
### 2️⃣ deliveries.csv


**Dataset Period:** 2008 – 2022
**Format:** CSV

## 🛠 Tools & Technologies Used

* **Power BI** – Dashboard development & visualization
* **Power Query** – Data cleaning & transformation
* **DAX** – Calculated measures and KPIs
* **Microsoft Excel** – Initial data inspection


## Project Workflow

### Step 1: Data Collection

Collected IPL datasets (2008–2022) from open-source platforms.

### Step 2: Data Cleaning

* Removed missing values
* Corrected inconsistent team names
* Converted data types
* Removed duplicate records

### Step 3: Data Transformation (Power Query)

* Merged matches and deliveries tables
* Created calculated columns
* Standardized season format
* Built relationships using match_id

### Step 4: Data Modeling

* Created relationship between:

  * Matches Table (Primary Key: match_id)
  * Deliveries Table (Foreign Key: match_id)
* Designed star schema model

### Step 5: Dashboard Creation

Developed interactive dashboards with filters and slicers for:

* Season
* Team
* Player
* Venue

##  Dashboard Sections

1. Team Performance Analysis
2. Batsman Performance Analysis
3. Bowler Performance Analysis
4. Toss Impact Analysis
5. Season-wise Trends
6. Venue Analysis


## Key Metrics Calculated

* Total Matches Played
* Total Wins
* Win Percentage
* Total Runs Scored
* Batting Strike Rate
* Bowling Economy Rate
* Total Wickets
* Toss Win Impact %

---

##  Key Insights

* Certain teams dominate across multiple seasons.
* Toss decisions influence match outcomes in specific venues.
* Total runs have increased in recent seasons.
* Some venues favor chasing teams.
* Individual player performance significantly impacts team success.
