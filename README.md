# Cyclistic 2024: Bike & E-Scooter Usage Analysis
Capstone project from the Coursera certification "Google Data Analytics Professional"

<img width="280" height="240" alt="image" src="https://github.com/user-attachments/assets/31acb175-e0e7-4404-897d-88c65ba73edf" />


## Google Data Analytics Capstone

This project is my capstone for the Google Data Analytics Professional Certificate.
This project is based on the 12 previous months of raw data (from January until December 2024 = 5.72 million rides). This project also required :

Handling the introduction of e-scooters in mid-2024

Performing full data cleaning, transformation, and visualization

Following the official data analysis cycle: Ask → Prepare → Process → Analyze → Share → Act

**Project Objective** : identify and understand behavioral differences between **annual members** (users with an annual membership) and **casual riders** (users without an annual membership).


## Business Objective

Cyclistic wants to increase the number of annual members.
To support a new marketing strategy, this analysis compares how casual riders and annual members use **classic bikes**, **electric bikes** and the newly introduced **electric scooters**.

## Dataset Overview

### Vehicle Types
- Classic bike
- Electric bike
- Electric scooter

### Station Data
- Start station name and ID
- End station name and ID

### Ride Data
- Start datetime
- End datetime
- Ride duration
- Month/day-of-week/hour (engineered features)

### User Type


## Key Insights

- Members ride more during weekdays and for commuting
- More casual riders during weekends and for longer leisure rides
- Scooters attract new casual users but show little adoption among members
- Membership-focused campaigns should target:
  - evening/weekend riders
  - scooter-first users
  - high-traffic tourist zones


## Tools & Skills Used

SQL for EDA/Cleaning and Processing (BigQuery)

Python for EDA (Pandas, Matplotlib)

Data Cleaning (handling nulls, merging 12 monthly datasets)

Feature Engineering (ride length, day of week, ride type)

Data Visualization

Business analytics and recommendation writing
