# Bellabeat: Smart Device Usage Analysis

**Google Data Analytics Professional Certificate — Capstone Project**  
Prepared by: Muhammad Zakaria Abbasi

## Project overview
This project analyzes Fitbit smart-device usage data to identify activity and sleep patterns and develop data-informed marketing recommendations for Bellabeat.

## Business task
Analyze smart-device usage trends and use the findings to recommend ways Bellabeat could encourage users to engage with its wellness app.

## Tools and approach
- **Google Sheets:** spreadsheet-based data cleaning, organization, calculations, aggregation, and analysis.
- **Data visualization:** charts and summary visuals used to communicate patterns in the presentation.
- **Business analysis:** interpreting findings and translating them into recommendations.

## Data
The project uses the public Fitbit Fitness Tracker dataset from Kaggle (CC0).

| Dataset | Records | Users | Purpose |
|---|---:|---:|---|
| Daily activity (raw) | 940 | 33 | Steps, distance, activity minutes, and calories |
| Sleep day (raw) | 413 | 24 | Sleep records, minutes asleep, and time in bed |
| Sleep day (cleaned export) | 410 | 24 | Duplicate-free sleep records used for analysis |

The cleaned sleep CSV contains the five analysis fields from the user's Google Sheets cleaning export. Spreadsheet helper/check columns are intentionally not included in this analysis-ready export.

## Key findings
1. Participants spent an average of approximately **956 minutes (15.9 hours) per day sedentary**.
2. **Tuesday and Saturday** had the highest average steps (8,949 and 8,947); **Sunday** had the lowest (7,627).
3. Steps and calories burned showed a **moderate positive correlation** (r = 0.56).
4. Sedentary minutes and sleep duration showed a **negative correlation** (r = -0.60) among the 24 users with sleep data.
5. Participants spent approximately 39 minutes per night in bed but not asleep (458 minutes in bed versus 419 minutes asleep).

These are associations and descriptive patterns; they do not establish causation.

## Recommendations
- Send movement reminders after long inactive periods, with stronger prompts on Fridays and Sundays.
- Encourage daily movement with step goals, streaks, and weekend challenges.
- Connect activity and sleep insights in the app, while avoiding claims that activity directly causes better sleep.
- Validate these directional findings using Bellabeat's own larger and more recent customer data.

## Repository structure
```text
bellabeat-smart-device-usage-analysis/
├── README.md
├── data/
│   ├── raw/
│   │   ├── dailyActivity_merged.csv
│   │   └── sleepDay_merged.csv
│   └── cleaned/
│       └── sleep_day_cleaned.csv
├── documentation/
│   └── analysis-notes.md
└── presentation/
    └── Bellabeat_Smart_Device_Usage_Analysis.pdf
```

## Limitations
- The activity dataset contains 33 users and the sleep dataset contains 24 users.
- The data covers April 12 to May 12, 2016, so it may not represent current device usage.
- Age and gender information are not available.
- The findings should be treated as directional rather than representative of all Bellabeat customers.

## Source and acknowledgement
Fitbit Fitness Tracker Data (Kaggle), released under the CC0 public-domain dedication. This project was completed as part of the Google Data Analytics Professional Certificate.
