# EDA_Cricket_Matches
🏏 IPL 2022 - Exploratory Data Analysis
A data analysis project exploring match-level data from the Indian Premier League (IPL) 2022 season to uncover insights into team performances, player stats, toss trends, and venue patterns.

📌 Project Overview
The Indian Premier League (IPL) is a professional T20 cricket league in India, featuring franchises representing cities across the country. This project performs an end-to-end Exploratory Data Analysis (EDA) on the IPL 2022 dataset to derive meaningful insights about match outcomes, player performances, and team dynamics.

📂 Dataset

File: IPL.csv
Records: 74 matches
Features: 20 columns

Key Columns
ColumnDescriptiondateDate of the matchvenueStadium where the match was playedstageMatch stage (group/qualifier/final)team1, team2Competing teamstoss_winnerTeam that won the tosstoss_decisionBat or field decision after tossfirst_ings_scoreScore in the first inningssecond_ings_scoreScore in the second inningsmatch_winnerWinning teamwon_byWin type — Runs or WicketsmarginWinning marginplayer_of_the_matchPlayer of the match award winnertop_scorerTop run-scorer in the matchhighscoreHighest individual scorebest_bowlingBest bowler of the matchbest_bowling_figureBowling figures (wickets–runs)

🔍 Analysis Performed
🏆 Team Performance

Which team won the most matches?
Win type distribution — wins by Runs vs Wickets

🪙 Toss Analysis

Toss decision trends (bat vs field)
Correlation between toss winner and match winner

🌟 Player Performances

Top 10 "Player of the Match" award winners
Top 2 run-scorers by cumulative high scores
Top 10 best bowling figures of the season

🏟️ Venue Analysis

Most matches hosted by venue

🎯 Custom Insights

Team with the highest winning margin by runs
Player with the highest individual score
Bowler with the best bowling figure


🛠️ Tech Stack

Python
Pandas — Data loading and manipulation
NumPy — Numerical operations
Matplotlib — Data visualization
Seaborn — Statistical plots


🚀 Getting Started

Clone the repository

bash   git clone https://github.com/your-username/ipl-2022-eda.git
   cd ipl-2022-eda

Install dependencies

bash   pip install pandas numpy matplotlib seaborn

Run the notebook

bash   jupyter notebook IPL22_EDA.ipynb

📊 Sample Visualizations

Bar chart of most match wins by team
Countplot of toss decisions
Horizontal bar chart of top Player of the Match winners
Venue-wise match count chart


📁 Project Structure
ipl-2022-eda/
│
├── IPL22_EDA.ipynb     # Main analysis notebook
├── IPL.csv             # Dataset
└── README.md           # Project documentation
