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
  ![{6F1E39A7-CAE2-4DC6-A1DC-EB589817A05B}](https://github.com/user-attachments/assets/c3deef54-f735-40cc-aa6d-31c3caaded3d)
- **Bowling Analysis**
  - Top wicket takers
  - Best bowling averages (min 10 wickets)
  - Best bowling figures in an innings
  - Most 5-wicket hauls
  - Best economy rates and strike rates
  - Most wides and no-balls by bowlers
  ![{74E69141-D9B2-4054-8FF3-CC0FE5D0B1E2}](https://github.com/user-attachments/assets/b758da6e-1f25-47d0-96a1-190b5b1f1345)
- **Fielding Analysis**
  - Most catches by fielders
  - Most dismissals by wicket-keepers
  ![{DDF7F3DF-65F5-41A1-A64B-D0BA1F66BF29}](https://github.com/user-attachments/assets/98b68f56-9e08-4700-b418-908c3d259870)
- **Team Analysis**
  - Total runs, most fours, most sixes by teams
  - Most runs conceded, most wickets, most wides, most catches by teams
  ![{AD6C4B36-74A4-47B6-AD14-42B8230CC3DA}](https://github.com/user-attachments/assets/10c285e3-5f62-4632-b452-6b5234ea5883)
- **Venue Analysis**
  - Batting and bowling friendly venues
  - Venues with most/least wickets per match
  ![{6A64CE94-1E9B-4699-874D-E0826905FC9A}](https://github.com/user-attachments/assets/51917600-ef26-430a-aad2-e65d17c88472)
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




