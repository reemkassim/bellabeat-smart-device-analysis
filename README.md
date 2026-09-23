# Bellabeat Smart Device Usage Analysis

## About Bellabeat

Bellabeat is a wellness technology company focused on helping women understand and improve their health and well-being through technology and data-driven insights. The company develops smart wellness products and digital tools that track areas such as activity, sleep, and other aspects of wellness.

## Project Overview

This project analyses smart device usage data to identify patterns in users' activity and sleep behaviour and develop data-driven recommendations for Bellabeat's marketing strategy.

The analysis was conducted using Microsoft Excel and Power Query, covering daily activity and sleep data from smart device users.

## Business Task

Analyse smart device usage data to identify trends in users' activity and sleep patterns, and use these insights to develop data-driven recommendations that could support Bellabeat's marketing strategy.

## Stakeholders

The key stakeholders for this analysis are:

- Bellabeat's Chief Creative Officer (CCO)
- Bellabeat's co-founder and executive team
- Bellabeat's marketing team

The analysis is intended to provide insights that can support marketing strategy and product engagement decisions.

## Dataset

The analysis used two cleaned datasets:

- Daily activity data covering approximately two months
- Daily sleep data covering approximately one month

The activity dataset included 33 unique users, while 24 users had sleep data.

## Data Preparation

The data was prepared using Microsoft Excel and Power Query.

The main data preparation steps included:

- Combined the two daily activity datasets
- Standardized date formats
- Removed duplicate records
- Checked for missing values
- Reviewed zero values and assessed their impact
- Created calculated fields such as:
  - Day of Week
  - Total Active Minutes
  - Total Active Hours
- Formatted the cleaned data into Excel tables
- Created PivotTables to support the analysis

 ## Analysis

The analysis focused on identifying patterns in daily activity, sedentary behavior, and sleep across the days of the week.

### Activity Analysis

Activity was analyzed using:

- Average steps by day of week
- Average total active minutes by day of week
- Average very active minutes by day of week
- Average fairly active minutes by day of week
- Average lightly active minutes by day of week
- Average sedentary minutes by day of week
- Average active minutes compared with sedentary minutes

### Sleep Analysis

Sleep was analyzed using:

- Average total sleep time
- Average time in bed
- Average sleep time by day of week
- Comparison of activity and sleep patterns across the days of the week

## Key Insights

### Activity Patterns

- Saturday had the highest average steps and total active minutes.
- Sunday had the lowest average steps and total active minutes.
- Sunday also had the lowest average very active, fairly active, and lightly active minutes.
- Sedentary time remained substantially higher than active time across all days of the week.
- Sedentary minutes were highest on Monday and lowest on Tuesday.

### Sleep Patterns

- Average sleep time varied across the days of the week.
- Sunday had the highest average sleep time.
- Thursday had the lowest average sleep time.
- Average sleep time was approximately 7 hours per day across the available sleep data.

### Activity and Sleep Patterns

Activity and sleep patterns were compared across the days of the week.

Sunday showed the lowest average activity and the highest average sleep time in the analysed data. This indicates that activity and sleep followed different weekly patterns within the available data.

This comparison describes observed patterns and does not establish a causal relationship between activity and sleep.

## Recommendations

Based on the observed patterns, the following recommendations could support Bellabeat's marketing strategy:

1. **Introduce weekend activity alerts or Sunday-specific activity challenges** to encourage users to remain active during periods of lower activity.

2. **Provide personalized bedtime reminders and weekly sleep reports** to encourage users to monitor and maintain consistent sleep habits.

3. **Introduce daily movement goals and inactivity reminders** to encourage users to break up long periods of sedentary behaviour.

## Dashboard

An Excel dashboard was created to present the main findings in a concise and visual format.

The dashboard includes:

- Key activity metrics
- Key sleep metrics
- Activity patterns by day of week
- Sleep patterns by day of week
- Activity and sleep pattern comparison
- Active versus sedentary minutes
- Key insights and recommendations

## Limitations

- The dataset contains a relatively small number of users.
- The activity and sleep datasets do not contain identical user populations. Activity data included 33 unique users, while 24 users had sleep data.
- The sleep data covers a shorter period than the activity data.
- The dataset may not be representative of all Bellabeat users.
- The analysis identifies patterns and associations in the available data but does not establish causation.
- The activity and sleep comparison should therefore be interpreted as a comparison of aggregate weekly patterns rather than a user-level causal relationship.

## Project Files

The repository contains the Excel workbook used for the analysis, including:

- Cleaned data
- Analysis tables
- Charts
- Dashboard
- Insights and recommendations

## Tools Used

- Microsoft Excel
- Power Query
- PivotTables
- Excel Charts

## Conclusion

The analysis identified clear differences in activity, sedentary behaviour, and sleep patterns across the days of the week.

The findings suggest opportunities for Bellabeat to encourage weekend activity, support consistent sleep habits, and promote regular movement throughout the day.
