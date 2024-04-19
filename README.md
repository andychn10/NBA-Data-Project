# NBA Data Project
## Overview
![newplot (2)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/5f5f51a7-a1b9-40fd-bc44-befc5b7a5576)
Before diving into any analytical studies of our database it is a great idea to get a general understanding of the correlatioon of statistical categories in the NBA.

We can observe a few positive correlations within our dataset:
- As the number of field goals made (FGM) goes up, the number of field goals attempted (FGA) goes up as well.
- As the number of FGM increase, the number of points scored (PTS) increases.
- Number of blocks increase, the number of rebounds increase as well. Normally the bigger players will be able to get blocks (BLK) and rebound (REB) the ball during the same possession.

Negative correlations:
- As the number of 3 point field goals made (3PTM) increase, the number of offensive rebounds (OREB) decrease - Generally, the players that are shooting and making 3 point shots are often smaller players or guards that do not grab many offensive rebounds.
- As the percentage of 3 point field goal attempts (3PTA) increase, the overall field goal percentage (FG%) decreases - We can interpret this as such: since the 3 point shot is further away it has a lower chance of going in, thus decreasing the overall field goal percentage.
- As the number of personal fouls (PF) increase, the number of minutes (MIN) played will decrease. Each player can only commit 6 fouls per game before they are fouled out, the more fouls they commit the less minutes they will play.

## How Are Minutes Distributed?
![newplot (3) (1) (1)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/d0d5c85d-6f93-4b28-a3fe-efcabd6db64b)


Taking a glance at the minutes distribution in the NBA, we see that in the regular season there is more even minutes distribution as teams are more inclined to try out different lineups and various combinations of players in search of wins. 

While both graphs are right-skewed, it is far more extreme in the playoffs as teams rely more on starpower and results-proven lineups. This can be attributed to a less evenly distributed graph in the playoffs and an increase in the percentage of players with less than 100 minutes played.

These observation can be clearly anlazyed in the third graphic, converting the data output to minutes per 48 minutes instead of total minutes played and overlapping the regular season minutes distribution to the playoffs minutes distribution. We can clearly see a significant increase in the percentage of players that play upwards of 35 minutes in the playoffs compare to the regular season.

## Points Distribution
![newplot (6)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/89cdf040-87a6-4bb0-b09b-047cff6d1a2a)
Looking at the graph above, we can observe an extermely right-skewed histogram, this indicates that over the past 10 years the NBA is still very reliant on their star players to produce large scoring outputs. This argument is even more extreme in the playoffs as we see the orange histogram overlap and extend past the blue histogram (Regular Season).

We see that in the playoffs the percentage of players scoring 20+ points per game increases significantly compare to the regular season, as well we see that there are a greater percentage of players that are scoring 0-2 points per game. This indicates a tighter rotation among NBA teams in the playoffs as they rely more on key players to provide scoring for their respective teams.

# How has the game changed over the past 10 years?
## Analyzing Statistics Per 48 Minutes For A Given Team

![Pace, FGA, AST, AST-TOV](https://github.com/andychn10/NBA-Data-Project/assets/137304001/fb2bf51d-07ca-478d-b3e0-c245558fd7c7)

Analyzing the trends from the past 10 years in the NBA, one of the most prominent changes is the increase in the pace of the game. The biggest indicator of this shift is the significant increase in possessions and field goals attempted (FGA). As teams play with a higher pace they do not utilize the full 24 second shot-clock instead, opting for quicker scoring opportunities resulting in more frequent shot attempts and changes in possession.

Another statistic that contributes to the pace of the game is assists, from 2012 to 2022 there is an increase of 3.2 assists per 48 minutes. Assists can be an indication of higher pace as teams can get easier scoring opportunities in transition and on fast breaks, allowing for more opportunities for assists. A supporting graphic for this argument is the assists to turnover ratio, there is a drastic upward trend in this metric from 2012 to 2022 indicating fewer turnovers and greater assists per 48 minutes. This supports the idea of teams getting easier scoring opportunities in transition allow for more assists and less turnovers.

![3PM, 3PA, 3PA%](https://github.com/andychn10/NBA-Data-Project/assets/137304001/f4bdfe95-49e8-4c32-a5ae-59b16b6706f8)


![TRU%, PT-FGA, 3PM-FGM](https://github.com/andychn10/NBA-Data-Project/assets/137304001/24a84df8-81c2-4a60-9a7d-48b817c02d62)

![REB,STL,BLK](https://github.com/andychn10/NBA-Data-Project/assets/137304001/0334ed8b-96d9-4c16-86be-092f3e057817)

