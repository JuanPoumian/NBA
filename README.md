# Data Science NBA Trends: Project Overview
I analyzed data from the NBA (National Basketball Association) and explored possible associations.

## Resources Used
**Python Version:** 3.9  
**Packages:** pandas, numpy, matplotlib, seaborn, scipy.stats

## Data 
Codecademy provided the data under the name **nba_games.csv** and contains the following variables:
* **game_id** - Unique ID for each game
* **year_id** - Season id, named based on year in which the season ended
* **fran_id** - Franchise id. Multiple team_ids can fall under the same fran_id due to name changes or moves. Interactive is grouped by fran_id
* **opp_fran** - Franchise id of opponent 
* **game_location** - Home (H), away (A), or neutral (N)
* **is_playoffs** - Flag for playoff games
* **pts** - Points scored by team
* **opp_pts** - Points scored by opponent
* **game_result** - Win or loss for team in the team_id column
* **forecast** - Elo-based chances of winning for the team in the team_id column, based on elo ratings and game location
* **point_diff** - the difference between pts and opp_pts

## EDA - en esta section explore los datos
I have thoroughly examined the dataframe and can confirm that no missing data was detected.

Then I calculated the difference between the average points scored by the Knicks and the Nets teams in 2010, below is a graphical representation of the information.


![2010seasonNK](https://user-images.githubusercontent.com/114705723/221719194-c397867b-a6b1-4f0a-a298-35dc97d5440d.png)


I also calculated the difference between the average points scored by the Knicks and the Nets teams in 2014. Below is a graphical representation of this information.


![2014season](https://user-images.githubusercontent.com/114705723/221719873-beac0a59-e725-43d8-a53d-59ba483d371c.png)

## Analyzing data from the year 2010 exclusively
finding relationship between franchise and points scored per game, Below is a graphical representation of this information.

![2010boxplot](https://user-images.githubusercontent.com/114705723/221721264-c204818d-0704-454a-9f62-f7c6b8cf78a1.png)

There's a relationship between the game result and the game location? 
