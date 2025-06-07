# IPL 2025 Data Analysis & Visualization

This project provides a comprehensive exploratory data analysis (EDA) and visualization dashboard for the IPL 2025 season, using ball-by-ball data stored in `ipl_2025.csv`. The code generates a variety of insightful plots for batsmen, bowlers, teams, venues, and fielders using Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## Features

- **Batting Analysis**
  - Top 10 run scorers
  - Top batting averages (min 120 balls faced)
  - Top strike rates (min 120 balls faced)
  - Most fours and sixes by batsmen
  - Top individual scores (single innings)
  - Best over-by-over scorers
- **Bowling Analysis**
  - Top wicket takers
  - Best bowling averages (min 10 wickets)
  - Best bowling figures in an innings
  - Most 5-wicket hauls
  - Best economy rates and strike rates
  - Most wides and no-balls by bowlers
- **Fielding Analysis**
  - Most catches by fielders
  - Most dismissals by wicket-keepers
- **Team Analysis**
  - Total runs, most fours, most sixes by teams
  - Most runs conceded, most wickets, most wides, most catches by teams
- **Venue Analysis**
  - Batting and bowling friendly venues
  - Venues with most/least wickets per match
---

## Requirements

- Python 3.7+
- pandas
- matplotlib
- seaborn
- numpy

Install dependencies with:
```bash
pip install pandas matplotlib seaborn numpy
```

---

## Data

- **Input:** `ipl_2025.csv`  
  The script expects a ball-by-ball dataset containing at least the following columns:
    - `striker`, `runs_of_bat`, `player_dismissed`, `wide`, `noballs`, `bowler`, `extras`, `match_id`, `innings`, `over`, `batting_team`, `bowling_team`, `fielder`, `wicket_type`, `venue`, `season`

---


## License

This project is provided for educational and analytical purposes.

---

## Credits

Developed by Rudra Rathod.  
Data source: IPL ball-by-ball data.

---




