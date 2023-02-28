# Data Science NBA Trends: Project Overview
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

## EDA In the section (in this file)
I explored the data and have thoroughly examined the dataframe. I can confirm that no missing data was detected.

## 2010  In the section (in this file)
For this analysis, I exclusively focused on the data from the 2010 dataframe, with the aim of gaining a comprehensive and detailed understanding of the specific trends and patterns of that particular year.
