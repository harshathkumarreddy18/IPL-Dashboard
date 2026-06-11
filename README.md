🏏 IPL Analytics Dashboard — Power BI
<img width="1377" height="786" alt="Screenshot 2026-06-11 155846" src="https://github.com/user-attachments/assets/aab3bb3c-ff11-493a-8d5d-4b01b89a0f32" />
📌 Project Overview

This is a multi-page interactive Power BI dashboard built on 18 seasons of IPL data (2008–2025). The project covers the full data analytics workflow — from raw CSV ingestion and data modelling to DAX measures and professional visual design.

Built as a portfolio project to demonstrate job-ready Power BI and data analytics skills.


📊 Dashboard Pages

1. 🏠 Overview


Total matches, seasons, teams, and cities at a glance
IPL title winners across all seasons
Season-wise match volume trend


2. 🏏 Batting Analysis


Top run scorers (V Kohli leads with 8,671 runs)
Strike rate and boundary % by player
Runs by batting style: Left-hand vs Right-hand


3. 🎳 Bowling Analysis


Top wicket takers (YS Chahal leads with 229 wickets)
Economy rate and bowling average comparisons
Wicket type breakdown: bowled, caught, LBW, etc.


4. 🤝 Team Performance


Win/loss record per team across all seasons
Toss impact analysis — toss winner wins 51.2% of matches
Head-to-head team comparisons


5. 📍 Match & Venue Insights


59 venues across 37 cities mapped
Ground-wise match count and win patterns
Home advantage analysis



⚙️ Technical Approach

Data Modelling


Star schema: ipl_matches_data as the central fact table
Relationships via match_id, player_id, and team_id
Optimised for cross-filter performance across all pages


Power Query (M)


Merged 4 CSV files into a unified model
Cleaned nulls, fixed data types, and standardised team names
Created calculated columns for match margin categories


DAX Measures


Win %, Strike Rate, Economy Rate, Batting Average, Bowling Average
Season-over-season trends using CALCULATE and FILTER
Dynamic titles and KPI labels using SELECTEDVALUE

