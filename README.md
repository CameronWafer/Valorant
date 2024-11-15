# In-Depth Analysis of Professional Valorant Scene

### Overview
This project involves a detailed data analysis of the current professional Valorant scene. The data is scraped from [VLR.gg](https://vlr.gg) using Selenium and filtered for the past 90 days (as of **November 14, 2024**).  

This is a continuous project—never fully complete but always progressing with new insights.

---

## Dataset Description: VLR.gg Professional Valorant Match Statistics
This dataset contains detailed statistics from professional Valorant matches, sourced from VLR.gg—a leading platform for tracking competitive Valorant tournaments, players, and teams. The data has been collected via web scraping techniques or manually curated based on publicly available match data.

---

## Variables in the Dataset

### **Match-Level Variables**
- **Match ID**: Unique identifier for each match.
- **Date**: The date when the match took place (format: YYYY-MM-DD).
- **Tournament Name**: Name of the tournament where the match occurred.
- **Team 1**: The name of the first team.
- **Team 2**: The name of the second team.
- **Score (Team 1)**: The total number of maps won by Team 1.
- **Score (Team 2)**: The total number of maps won by Team 2.
- **Map Name**: The specific map played during a match (e.g., Haven, Bind).
- **Duration**: Length of the map/match in minutes.

---

### **Player-Level Variables**
- **Player Name**: The in-game name (IGN) of the player.
- **Team**: The team to which the player belongs during the match.
- **Agent**: The character selected by the player for the map.
- **Kills**: Total number of eliminations made by the player.
- **Deaths**: Total number of times the player was eliminated.
- **Assists**: Number of assists recorded by the player.
- **ACS**: Average Combat Score, a key performance metric in Valorant.
- **ADR**: Average Damage per Round.
- **Headshot %**: Percentage of eliminations made via headshots.

---

### **Agent-Level Variables**
- **Agent Name**: The name of the agent (e.g., Jett, Omen).
- **Pick Rate**: Percentage of matches in which the agent was selected.
- **Win Rate**: Percentage of matches won when this agent was used.
- **Average ACS**: The mean ACS for the agent across all matches.

---
