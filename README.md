🏏 Indian Premier League (IPL) Match Data (2008–2016)

A comprehensive dataset of all Indian Premier League cricket matches and ball-by-ball data from Season 1 (2008) to Season 9 (2016).

📊 Dataset Overview

📁 File Name

matches.csv	(Summary of each match including teams, venue, date, result, and umpires)
deliveries.csv	(Ball-by-ball level data including batsman, bowler, runs scored, dismissals, etc.)

🗂️ File Details

📌 matches.csv – Match Summary

🔹 id: Unique match ID

🔹 season: IPL season year

🔹 city: City where match was played

🔹 date: Match date

🔹 team1, team2: Contesting teams

🔹 toss_winner, toss_decision: Toss results

🔹 winner: Match winner

🔹 result, dl_applied: Result type and D/L method

🔹 player_of_match: Best performer

🔹 venue: Stadium

🔹 umpire1, umpire2: Umpire names


📌 deliveries.csv – Ball-by-Ball Data

🔸 match_id, inning: Match and inning ID

🔸 batting_team, bowling_team

🔸 over, ball: Over and ball number

🔸 batsman, non_striker, bowler

🔸 runs: Total runs, extras, and batsman runs

🔸 dismissal_kind, player_dismissed: Dismissal info


📌 Exploratory Data Analysis (EDA) Questions

Below are some insightful questions I explored using pandas and matplotlib/seaborn:


🧠 Match-Level Analysis (matches.csv)

🔹 How many matches were played in each IPL season?

🔹 Which teams have won the most number of matches?

🔹 Which venue hosted the most matches?

🔹 How many times did teams win the toss and also win the match?

🔹 Who are the top 10 players with the most "Player of the Match" awards?

🔹 What is the most successful team overall (by total wins)?


🎯 Ball-by-Ball Analysis (deliveries.csv)

🔸 Who are the top 10 highest run scorers?

🔸 Which bowlers have taken the most wickets?

🔸 What is the average number of runs scored per over across all seasons?

🔸 Which batsmen have the best strike rate (min 500 balls faced)?

🔸 Which bowler has the best economy rate (min 200 overs bowled)?

🔸 What is the distribution of different dismissal types (caught, bowled, lbw, etc.)?


📊 Combined Insights

🟢 Which team scores the most in powerplays (first 6 overs)?

🟢 What is the average winning margin (by runs/wickets) per team?

🟢 What is the most common toss decision (bat/field) per season?




🗂 Project Structure

**📂 data/**
- `matches.csv`
- `deliveries.csv`

**📂 notebooks/**
- `ipl_eda_analysis.ipynb` ← Answers all above questions


📄 `README.md`  
📄 `requirements.txt`



📥 Dataset Source

🔗 https://www.kaggle.com/datasets/manasgarg/ipl/data

🏁 Conclusion

This dataset provides a rich source of IPL data for cricket fans, analysts, and data scientists. It enables insightful exploration, powerful predictions, and exciting visual storytelling in the world of T20 cricket.
