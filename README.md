# Bellabeat-Case-Study
Bellabeat smart device usage analysis using Python, Pandas and Tableau.
# Bellabeat Smart Device Usage Analysis
<img width="1009" height="800" alt="image" src="https://github.com/user-attachments/assets/3dba3b78-687d-4ccf-adad-9c3dd69dacc4" />


## Project Overview

This project analyzes Fitbit smart-device usage data to understand users' activity and sleep patterns and develop marketing recommendations for the Bellabeat App.

The analysis focuses on daily activity, steps, calories, sedentary time, and sleep duration.

## Business Task

The main objective is to identify trends in smart-device usage and use these insights to support Bellabeat's marketing strategy.

### Key Questions

- What are the main trends in smart-device usage?
- How could these trends apply to Bellabeat customers?
- How could these trends influence Bellabeat's marketing strategy?

## Dataset

The analysis uses the **FitBit Fitness Tracker Data** provided for the Bellabeat case study.

The main datasets used were:

- `activity_cleaned.csv` — cleaned daily activity data
- `sleep_cleaned.csv` — cleaned daily sleep data
- `bellabeat_tableau.csv` — dataset prepared for Tableau visualization

The activity data contains **940 daily records**, while the cleaned sleep data contains **410 records**.

After merging activity and sleep data by user ID and date, the final analysis dataset contained **410 matched records**.

## Tools Used

- **Python**
- **Pandas**
- **Tableau**
- **Jupyter Notebook**

## Data Cleaning & Preparation

Python and Pandas were used to:

- Load the activity and sleep datasets
- Check missing values and duplicate records
- Convert date columns to datetime format
- Remove 3 exact duplicate sleep records
- Check data consistency and potential data-quality issues
- Merge activity and sleep data using user ID and date
- Create activity-level categories
- Create sleep-duration categories
- Create sedentary-time categories

## Analysis

The analysis explored:

- Daily step patterns
- Activity levels
- Calories burned
- Sedentary time
- Sleep duration
- Relationship between sleep duration and daily steps
- Average calories across sleep-duration groups
- Activity patterns across days of the week

## Key Findings

### Weekly Activity

Saturday recorded the highest average steps in the activity-sleep matched dataset, while Sunday recorded the lowest.

### Sleep & Activity

Sleep duration and daily steps showed a weak negative correlation of approximately **-0.19**.

This indicates a weak relationship and does not establish causation.

### Sleep & Calories

The **6–8 hour sleep group** recorded the highest average calories at approximately **2,525 calories**.

### Activity Levels

Within the 410 matched activity and sleep records:

- High activity: 165 records
- Moderate activity: 149 records
- Low activity: 96 records

## Tableau Dashboard

A Tableau dashboard was created to visualize the main activity and sleep patterns.

The dashboard includes:

- Average Steps by Day
- Activity Level Distribution
- Sleep Duration vs. Daily Steps
- Average Calories by Sleep Duration

## Marketing Recommendations

### 1. Encourage Consistent Weekly Activity

Bellabeat could use weekly goals, activity reminders, and short challenges to encourage users to maintain regular activity throughout the week.

### 2. Combine Sleep and Activity Insights

The Bellabeat App could present sleep and activity information together to help users understand their personal wellness patterns.

### 3. Encourage Breaks from Prolonged Inactivity

Bellabeat could use gentle movement reminders and short activity challenges to encourage users to break up periods of inactivity.

## Limitations

- The dataset has a relatively small sample and may not represent all Bellabeat customers.
- Activity and sleep data were available for different numbers of users.
- Fitbit data may contain tracking and measurement limitations.
- The analysis identifies patterns and relationships but does not establish causation.

## Project Files

| File | Description |
|---|---|
| `activity_cleaned.csv` | Cleaned daily activity dataset |
| `sleep_cleaned.csv` | Cleaned sleep dataset |
| `bellabeat_tableau.csv` | Dataset prepared for Tableau |
| `bellabeat_analysis.ipynb` | Python and Pandas analysis |
| `Bellabeat_Presentation.pptx` | Project presentation |
| `README.md` | Project documentation |

## Conclusion

The analysis identified patterns in activity and sleep behavior within the available Fitbit data.

These findings suggest opportunities for Bellabeat to use its app to provide personalized activity and sleep insights, weekly goals, and movement reminders.

This project demonstrates a complete data analysis workflow from data cleaning and exploration to visualization and business recommendations.
