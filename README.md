# Data Science NBA Trends: Project Overview

![NBA-logo-png-download-free-1200x675](https://user-images.githubusercontent.com/114705723/221735255-75c1e737-8a77-4745-9243-a35ce902ca35.png)

I analyzed data from the NBA (National Basketball Association) and explored possible associations.

## Data
Codecademy provided the data under the name **nba_games.csv** and contains the following variables:
* **game_id** - Unique ID for each game.
* **year_id** - Season id, named based on year in which the season ended.
* **fran_id** - Franchise id, multiple team_ids can fall under the same fran_id due to name changes or moves, Interactive is grouped by fran_id.
* **opp_fran** - Franchise id of opponent .
* **game_location** - Home (H), away (A), or neutral (N).
* **is_playoffs** - Flag for playoff games.
* **pts** - Points scored by team.
* **opp_pts** - Points scored by opponent.
* **game_result** - Win or loss for team in the team_id column.
* **forecast** - Elo-based chances of winning for the team in the team_id column, based on elo ratings and game location.
* **point_diff** - the difference between pts and opp_pts.

## Resources Used
**Python Version:** 3.9  
**Packages:** pandas, numpy, matplotlib, seaborn, scipy.stats

## EDA
The EDA.ipynb file in the repository was responsible for conducting exploratory data analysis on the dataset.
I can confirm that no missing data was detected.

## 2010
The 2010.ipynb in the repository exclusively analyzes the data from the 2010 dataframe, providing insights and observations specific to that year.
