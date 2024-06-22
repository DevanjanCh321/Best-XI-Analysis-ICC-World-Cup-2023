# ICC Men's Cricket World Cup: Best 11 Analysis

## Project Description

This project focuses on analyzing player performances from the ICC Men's Cricket World Cup using comprehensive statistical analysis. The goal is to identify the best 11 players based on their batting, bowling, and all-round abilities, leveraging detailed data exploration and visualization techniques.

## Data Sources

### Datasets:

- **df**: Contains batting statistics such as Match Number, Batsman Name, Runs Scored, Balls Faced, etc.
- **df1**: Includes bowling statistics including Match Number, Bowler Name, Overs Bowled, Runs Given, Wickets Taken, etc.

## Project Steps

1. **Data Cleaning and Preprocessing**
   - Importing data from CSV files and using Pandas for initial data exploration.
   - Cleaning datasets to handle missing values, convert data types, and ensure data consistency.

2. **Batting Statistics (`bat_stat`)**

   - Calculating batting metrics for each batsman:
     - Total Runs Scored
     - Total Matches Played
     - Batting Average (Runs / Dismissals)
     - Batting Strike Rate (100 * Runs / Balls Faced)

   - Renaming and aggregating data to summarize individual batting performances.

3. **Bowling Statistics (`bowler_stat`)**

   - Deriving bowling metrics for each bowler:
     - Total Wickets Taken
     - Total Overs Bowled (converted from Overs format)
     - Total Runs Given
     - Bowling Economy Rate (Runs Given / Overs Bowled)
     - Bowling Average (Runs Given / Wickets Taken)
     - Bowling Strike Rate (Total Balls Bowled / Wickets Taken)

4. **Data Merging and All-Rounder Identification**

   - Merging `bat_stat` and `bowler_stat` datasets based on common player names to identify all-rounders.
   - Applying filters and conditions to identify top all-round performers based on batting and bowling criteria.

5. **Visualization and Exploratory Data Analysis (EDA)**

   - Utilizing Matplotlib for creating insightful visualizations:
     - Bar charts and line plots to visualize batting statistics (Runs, Batting Average).
     - Charts depicting bowling statistics (Wickets, Economy Rate).
     - Interactive visualizations for individual player analysis, highlighting top performers and performance trends.

6. **Best 11 Selection**

   - Analyzing criteria for selecting the best 11 players based on comprehensive performance metrics in batting, bowling, and all-round abilities.
   - Applying advanced filtering and sorting techniques to identify top players suitable for specific roles in the team (e.g., batsmen, bowlers, all-rounders).

## Conclusion

This project showcases advanced data analysis capabilities using Python and Pandas, demonstrating proficiency in statistical calculations, data visualization, and exploratory data analysis within the context of cricket tournament statistics. The insights gained facilitate informed decisions for team selection and player performance evaluation in international cricket tournaments like the ICC Men's Cricket World Cup.
