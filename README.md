# 📊 Google Data Analytics Capstone Project – Cyclistic Case Study

This project was completed as part of the **Google Data Analytics Professional Certificate**. The objective is to analyze data from a bike-share company and generate insights to help improve its marketing strategy.

---

## 🧰 Tools Used

| Tool           | Purpose                                      |
|----------------|----------------------------------------------|
| Excel          | Initial data inspection                      |
| PostgreSQL     | Data cleaning, transformation, and analysis  |
| Power BI       | Interactive dashboards and visual exploration|

---

## 📁 Dataset Overview

The dataset includes 12 `.csv` files containing ride details from **May 2024 to April 2025**. Each file includes trip start and end times, stations, rideable types, and user types (member vs casual).

---

## 🔍 Initial Steps

1. **Excel Data Review**
   - Checked for nulls, duplicates, and unusual values
   - Verified column formats and consistency
   - Merged all monthly data into a single dataset

2. **PostgreSQL Cleaning & Preparation**
   - Loaded data into PostgreSQL
   - Removed trips with missing IDs or negative durations
   - Created new columns:
     - `ride_minutes` (trip duration in minutes)
     - `hour_of_day`, `day_of_week`, `month`
   - Replaced null values and standardized user types

3. **Power BI Visualization**
   - Connected PostgreSQL to Power BI
   - Built interactive visual dashboards to explore:
     - Number of rides by user type and time
     - Average trip duration
     - Most common start/end stations
     - Ride trends by weekday and month

---


