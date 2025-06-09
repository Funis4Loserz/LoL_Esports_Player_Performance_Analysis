# LoL_Esports_Player_Performance_Analysis
An exploratory data analysis project examining player performance correlations with team success in the 2024 League of Legends World Championship, using Python and Power BI.
______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

VSCode For README.md
______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Jupyter Notebook Main Code Using Python

* `1_LoL_Player_Stats_Cleaning_EDA.ipynb`: Jupyter Notebook containing Python code for data cleaning, preprocessing, and EDA.
* `data/player_stats_cleaned_for_powerbi.csv`: The cleaned and preprocessed dataset used for the Power BI dashboard.
* `LoL_Esports_Player_Performance_Analysis.pbix`: The Power BI Desktop file containing the dashboard source.
______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Project Title: # LoL Esports Player Performance Analysis

This project performs an exploratory data analysis (EDA) on player statistics from the 2024 League of Legends World Championship. The goal is to understand how individual player performance metrics correlate with overall team success. The analysis involves data cleaning, feature engineering, and visualization using Python (Pandas, Matplotlib, Seaborn), culminating in an interactive dashboard built with Power BI.

The dataset used for this analysis is "2024 LoL Championship Player Stats & Swiss Stage" obtained from Kaggle.
(https://www.kaggle.com/datasets/anmatngu/2024-lol-championship-player-stats-and-swiss-stage)

* How do specific player performance metrics (e.g., KDA, GPM, DPM) vary across different positions?
* Is there a correlation between individual player performance (KDA) and their team's win rate?
* Which teams or players exhibited top performance based on key statistical indicators?

**Data Acquisition:** Downloaded player statistics from Kaggle.
**Data Cleaning & Preprocessing (Python):**
* Loaded data using Pandas.
* Identified and handled incorrect data types.
* Engineered new features such as KDA Ratio and a Win Indicator.
**Exploratory Data Analysis (Python):**
* Calculated aggregated statistics for player positions and teams.
* Generated various visualizations (histograms, scatter plots, box plots, bar charts, correlation matrix) to explore relationships using Matplotlib and Seaborn.
**Dashboard Creation (Power BI):**
* Exported cleaned data to CSV.
* Developed an interactive multi-page dashboard to present key insights visually.



Power BI Charts And Indicators
My Insights from the Chart

### Live Interactive Dashboard
Explore the interactive dashboard here:
(https://app.powerbi.com/groups/me/reports/6aafebf5-b700-4347-86ad-93abaa112b8b/dfd0bab0250beabaf42e?experience=power-bi)

Page 1: Overall Performance
1: The analysis of the 2024 LoL Championship revealed an average KDA of X and an average Win Rate of Y% across all players, indicating a highly competitive environment.
2: A strong positive correlation was observed between a player's KDA and their Win Rate, confirming that superior individual performance in terms of kills and assists relative to deaths significantly contributes to team victories.
3: Team [T1] and Team [Gen.G] consistently appeared in the top rankings for both average KDA and average Win Rate, suggesting their cohesive team play and individual talent led to their dominance.

Page 2: Position Breakdown
1: Mid Laners and AD Carries generally exhibited the highest average KDA ratios, likely due to their primary damage-dealing roles, while Supports often had lower KDA but high Vision Score per Minute.
2: Top Laners and Junglers showed a wider distribution of KDA and GPM, indicating more variance in individual impact or playstyles within those positions.
3: While not directly correlated with KDA, Gold Per Minute (GPM) was a strong indicator of a player's economic advantage, especially for Mid and AD Carry roles, driving their ability to carry games.