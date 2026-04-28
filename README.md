# IPL Data Analysis

This project analyzes Indian Premier League (IPL) match and ball-by-ball data to uncover patterns in team performance, match-winning strategies, player impact, and scoring behavior across seasons.

## Project Objective

The objective of this project is to perform exploratory data analysis on IPL data and identify key insights related to:

- Team performance trends
- Match-winning factors
- Toss impact
- Batting and chasing patterns
- Player performance
- Venue-based scoring behavior

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI *(dashboard to be added)*

## Dataset

The project uses two datasets:

- `matches.csv` → Match-level IPL data
- `deliveries.csv` → Ball-by-ball IPL data

## Data Cleaning

The following preprocessing steps were performed before analysis:

- Handled missing values
- Standardized date formats
- Checked and removed duplicates
- Standardized inconsistent team names
- Converted relevant columns into appropriate data types

## Exploratory Data Analysis

The analysis includes the following key areas:

1. Team Wins Analysis  
2. Toss Impact Analysis  
3. Batting First vs Chasing Analysis  
4. Top Run Scorers  
5. Top Wicket Takers  
6. Runs per Over Analysis  
7. Venue-wise Average Score  
8. Player Impact Analysis (PoTM vs Matches Played)

## Key Insights

- Mumbai Indians and Chennai Super Kings have been the most successful IPL franchises.
- Winning the toss provides a slight advantage, but it is not a decisive predictor of match outcomes.
- Teams have historically won more matches while chasing.
- A small group of elite batters and bowlers consistently dominate performance metrics.
- IPL scoring follows a clear tactical pattern: aggressive starts, controlled middle overs, and accelerated death overs.
- Venue conditions significantly influence match scoring patterns.
- Comparing Player of the Match awards with matches played highlights the difference between longevity and match-winning efficiency.

## Project Structure

```text
ipl-data-analysis/
│
├── matches.csv
├── deliveries.csv
├── main.ipynb
└── README.md
```
