# In-Depth Analysis of Professional Valorant Scene

### Overview
This project involves a detailed data analysis of the current professional Valorant scene. The data is scraped from [VLR.gg](https://vlr.gg) using Selenium and filtered for the past 90 days (as of **November 14, 2024**).  

This is a continuous project—never fully complete but always progressing with new insights.

---

# Integrated OpenAI LLM for Player Performance Analysis (UPDATED)

- Added OpenAI GPT API integration to generate natural language summaries for each player's performance.
- Summaries highlight key stats (ACS, K/D Ratio, KAST, etc.), notable achievements, and improvement areas.
- Outputs are stored in the results and formatted for easy review.
- Improved interpretability of player stats through automated, detailed insights.

Code not publically availible as to not publically release my OpenAI API key, message me on LinkedIn for more details: https://www.linkedin.com/in/cameron-hafer/
- Sample output located at bottom of README

---

## Dataset Description: VLR.gg Professional Valorant Match Statistics
This dataset contains detailed statistics from professional Valorant matches, sourced from VLR.gg—a leading platform for tracking competitive Valorant tournaments, players, and teams.

---

## Variables

- **Rnd**: Total rounds played in the match.
- **R2.0**: Rating 2.0, an overall performance rating in Valorant (aggregated score).
- **ACS**: Average Combat Score, measures in-game performance based on kills, assists, and damage.
- **K:D**: Kill-to-Death ratio, the number of kills per death.
- **KAST**: Percentage of rounds with a kill, assist, survived, or traded involvement.
- **ADR**: Average Damage per Round, damage dealt per round.
- **KPR**: Kills Per Round, average kills per round.
- **APR**: Assists Per Round, average assists per round.
- **FKPR**: First Kills Per Round, average first kills per round.
- **FDPR**: First Deaths Per Round, average first deaths per round.
- **HS%**: Headshot Percentage, percentage of kills achieved via headshots.
- **CL%**: Clutch Percentage, percentage of successful clutch rounds.
- **CL**: Number of clutch rounds won.
- **KMax**: Maximum kills in a single round.
- **K**: Total kills in the match.
- **D**: Total deaths in the match.
- **A**: Total assists in the match.
- **FK**: Total first kills in the match.
- **FD**: Total first deaths in the match.

---

#### Sample LLN Output for a player

### Player Performance Summary: florescent SR on Neon

#### Overall Performance:
- **Rating 2.0**: 1.38
- **ACS**: 293.90
- **K/D Ratio**: 1.64
- **KAST**: 80.00%
- **ADR**: 188.40
- **KPR**: 1.02
- **FKPR**: 0.27
- **CL%**: 17.00%
- **HS%**: 0.32%

#### Notable Achievements and Strengths:
1. **Consistent Performance**: With a **Rating 2.0** of 1.38, florescent SR on Neon has been consistently impactful in matches over the last 60 days.
  
2. **Team Player**: A high **KAST** of 80.00% suggests florescent SR actively participates in rounds, either by getting kills, assists, surviving, or getting traded.

3. **Entry Fragger Potential**: Having a **KPR** of 1.02 and **FKPR** of 0.27 indicates that florescent SR is successful in securing initial picks, providing crucial advantages to the team.

4. **Clutch Ability**: A **CL%** of 17.00% showcases the player's ability to thrive in high-pressure situations, potentially turning the tides of rounds in favor of their team.

5. **Aim Prowess**: With an **ACS** of 293.90 and **ADR** of 188.40, florescent SR exhibits strong mechanical skills and consistent damage output, making them a formidable presence in engagements.

#### Areas for Improvement:
1. **Headshot Accuracy**: Despite being an overall strong performer, a **HS%** of 0.32% indicates room for improvement in aiming for crucial headshots to secure quicker kills and maintain an advantage in duels.

2. **Minimizing Deaths**: While the **K/D Ratio** is positive at 1.64, reducing the total deaths (318) could further enhance florescent SR's impact, ensuring more consistent presence in crucial rounds.

#### Summary:
florescent SR on Neon impresses with their consistent and impactful performance, showcasing strengths in teamwork, entry fragging, clutch scenarios, and mechanical skills. To further elevate their gameplay, focusing on enhancing headshot accuracy, minimizing deaths, and continuing to refine their skills will solidify florescent SR as a formidable force on the battlefield.
---
