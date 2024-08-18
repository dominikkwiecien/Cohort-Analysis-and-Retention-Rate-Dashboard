# Cohort Analysis and Retention Rate Dashboard

This project is a Google Sheets-based analytical dashboard designed to perform cohort analysis and retention rate calculations for user activity data. The dashboard uses pivot tables and dynamic formulas to display insights into user retention over time, segmented by different dimensions such as game type, activity type, and user language.

## Project Overview

The goal of this project is to analyze user behavior over time, particularly focusing on how well the platform retains users across different cohorts. The project is structured to facilitate easy visualization and interpretation of retention metrics, which are crucial for understanding user engagement and improving product strategies.

### Key Features

1. **Cohort Analysis**:

   - The core of this project is the cohort analysis table, which groups users based on their first activity month and tracks their engagement in subsequent months.
   - The pivot table dynamically displays the number of unique users for each cohort across different months.

2. **Retention Rate Calculation**:

   - A secondary table calculates the retention rate for each cohort, showing the percentage of users who returned in subsequent months compared to their cohort's first month.
   - This table is linked to the pivot table, ensuring that any changes in the pivot table automatically reflect in the retention rate calculations.

3. **Dynamic Table Sizing**:

   - The retention rate table automatically adjusts its size based on the pivot table, expanding or contracting as needed.
   - This is achieved using the `IF` function to conditionally display data.

4. **Conditional Formatting**:

   - Both the pivot table and the retention rate table are enhanced with conditional formatting to highlight trends, such as identifying months with the highest and lowest user retention.
   - This visual aid makes it easier to spot critical patterns at a glance.

5. **Interactive Filters**:
   - Slicers are added next to the tables to filter the data by game name, activity type, and user language.
   - These slicers allow for a more granular analysis, making it possible to explore how different segments of the user base behave over time.

### File Structure

- **activity**: Contains the raw data of user activities, including the date of activity, type of activity, and user details.
- **Retention rate**: The table where retention rates are calculated and displayed.
- **Cohort analysis**: The pivot table that aggregates user activity data for cohort analysis.
- **activity types**: Additional data related to the types of activities users engage in.
- **DAU, WAU**: Tables summarizing daily and weekly active users, respectively.

### How to Use

- Download and open the `Cohort Analysis and Retention Rate Dashboard.xlsx` file to explore the data and charts.
- Use the data and charts to understand user activity trends and the effectiveness of predictions.

### Applications

This project is ideal for product managers, data analysts, and marketers looking to understand user engagement and retention. It provides a powerful yet straightforward way to monitor user retention and identify areas for improvement.
