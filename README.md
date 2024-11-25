# In-Depth Analysis of Professional Valorant Scene

### Overview
This project involves a detailed data analysis of the current professional Valorant scene. The data is scraped from [VLR.gg](https://vlr.gg) using Selenium and filtered for the past 90 days (as of **November 14, 2024**).  

This is a continuous project—never fully complete but always progressing with new insights.

---

# feat: Integrated OpenAI LLM for Player Performance Analysis (UPDATED)

- Added OpenAI GPT API integration to generate natural language summaries for each player's performance.
- Summaries highlight key stats (ACS, K/D Ratio, KAST, etc.), notable achievements, and improvement areas.
- Outputs are stored in the results and formatted for easy review.
- Improved interpretability of player stats through automated, detailed insights.

Code not publically availible as to not publically release my OpenAI API key, message me on LinkedIn for more details: https://www.linkedin.com/in/cameron-hafer/

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
