IPL 2025 Data Analysis
Overview

This project analyzes the IPL 2025 dataset (matches.csv) to uncover insights about team performances, toss decisions, top players, and match statistics. The analysis is performed in Python using Pandas, NumPy, Matplotlib, and Seaborn.

The goal is to explore the dataset, clean it for inconsistencies, and visualize trends such as match-winning teams, best players, and venues with the most matches.

Technologies Used

Python 3
Pandas – Data handling and cleaning
NumPy – Numerical operations
Matplotlib & Seaborn – Data visualization

Dataset

The dataset used is matches.csv, which contains IPL 2025 match-level details.

Key columns include:
match_id – Unique identifier for each match
match_winner – Team that won the match
toss_winner, toss_decision – Toss details
player_of_the_match – Man of the Match
top_scorer, highscore – Batting statistics
best_bowling, best_bowling_figure – Bowling performance
venue – Venue of the match
Columns wb_runs and wb_wickets were dropped due to excessive missing values.

Key Analyses & Visualizations

1.Most Matches Won by Teams
2.Bar chart showing which teams secured the highest number of wins.
3.Toss Decision Trends
4.Analysis of batting vs fielding choice after winning the toss.
5.Impact of Toss on Match Result
6.Percentage of matches where toss winners also won the game.
7.Top Man of the Match Award Winners
8.Top 10 players who received the most Man of the Match awards.
9.Top Scorers
10.Highest aggregate runs by players.
11.Best Bowling Figures
12.Players with the best bowling records in terms of wickets taken.
13.Most Popular Venues
14.Venues with the highest number of matches played.
15.Record Performances
16.Player with the highest individual score.
17.Bowler with the best bowling figure.

Sample Visuals

Team win distribution (barplot)
<img width="1238" height="926" alt="image" src="https://github.com/user-attachments/assets/54320760-53f9-4f21-bbd4-07afd0922659" />


Toss decision trends (countplot)
<img width="1090" height="841" alt="image" src="https://github.com/user-attachments/assets/fed68cc9-5789-4c15-b140-4791d4ca9364" />


Top scorers and bowlers (bar charts)
<img width="1241" height="821" alt="image" src="https://github.com/user-attachments/assets/f526f1e3-4271-463f-9e8a-b481222c0c80" />


Venue popularity (horizontal bar chart)
<img width="1508" height="818" alt="image" src="https://github.com/user-attachments/assets/085ff982-0782-4c2e-b5d2-0f7e4cd486df" />


How to Run

Clone the repository:

git clone https://github.com/Pushkin4000/IPL_2025_DataAnalysis.git


Navigate to the project folder:

cd IPL_2025_DataAnalysis


Install required libraries:

pip install pandas numpy matplotlib seaborn


Run the Jupyter Notebook:

jupyter notebook IPL_2025.ipynb

Future Improvements to be added

1.Add interactive dashboards using Plotly/Streamlit.
2.Expand to player-wise career statistics.
3.Build a predictive model for match outcomes.
