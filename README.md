# IPL 2025 Data Analysis

## Overview

This project analyzes the **IPL 2025 dataset (`matches.csv`)** to uncover insights about team performances, toss decisions, top players, and match statistics.

The analysis is performed in **Python** using **Pandas, NumPy, Matplotlib, and Seaborn**.

The goal is to:

* Clean the dataset and handle inconsistencies
* Explore team and player performance
* Visualize trends such as match-winning teams, best players, and most frequent venues

---

## Technologies Used

* Python 3
* Pandas – Data handling and cleaning
* NumPy – Numerical operations
* Matplotlib & Seaborn – Data visualization

---

## Dataset

The dataset used is `matches.csv`, which contains IPL 2025 match-level details.

**Key columns include:**

* `match_id` – Unique identifier for each match
* `match_winner` – Team that won the match
* `toss_winner`, `toss_decision` – Toss details
* `player_of_the_match` – Man of the Match
* `top_scorer`, `highscore` – Batting statistics
* `best_bowling`, `best_bowling_figure` – Bowling performance
* `venue` – Venue of the match

> Note: Columns `wb_runs` and `wb_wickets` were dropped due to excessive missing values.

---

## Key Analyses & Visualizations

1. **Most Matches Won by Teams** – Bar chart showing which teams secured the highest number of wins
2. **Toss Decision Trends** – Analysis of batting vs fielding choices after winning the toss
3. **Impact of Toss on Match Result** – Percentage of matches where toss winners also won the game
4. **Top Man of the Match Award Winners** – Top 10 players with the most awards
5. **Top Scorers** – Highest aggregate runs by players
6. **Best Bowling Figures** – Top 10 players with the best bowling performances
7. **Most Popular Venues** – Venues with the highest number of matches played
8. **Record Performances**

   * Highest individual batting score
   * Best bowling figure

---

## Sample Visuals  

### Team win distribution (barplot)  
<img width="600" src="https://github.com/user-attachments/assets/54320760-53f9-4f21-bbd4-07afd0922659" />  

### Toss decision trends (countplot)  
<img width="600" src="https://github.com/user-attachments/assets/fed68cc9-5789-4c15-b140-4791d4ca9364" />  

### Top scorers and bowlers (bar charts)  
<img width="600" src="https://github.com/user-attachments/assets/f526f1e3-4271-463f-9e8a-b481222c0c80" />  

### Venue popularity (horizontal bar chart)  
<img width="600" src="https://github.com/user-attachments/assets/085ff982-0782-4c2e-b5d2-0f7e4cd486df" />  


## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Pushkin4000/IPL_2025_DataAnalysis.git
   ```

2. Navigate to the project folder:

   ```bash
   cd IPL_2025_DataAnalysis
   ```

3. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Run the Jupyter Notebook:

   ```bash
   jupyter notebook IPL_2025.ipynb
   ```

---

## Future Improvements

* Add interactive dashboards using Plotly/Streamlit
* Expand to player-wise career statistics
* Build a predictive model for match outcomes

---
