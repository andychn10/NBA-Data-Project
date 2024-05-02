# Decade in Review: Exploring NBA Trends and Performance (2010-2020)
## Overview
![newplot (2)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/5f5f51a7-a1b9-40fd-bc44-befc5b7a5576)
Before delving into any analytical studies of our database, it's essential to gain a general understanding of the correlation among statistical categories in the NBA.

We can identify several positive correlations within our dataset:

- An increase in the number of field goals made (FGM) is accompanied by a rise in the number of field goals attempted (FGA).
- As the number of FGM increases, so does the number of points scored (PTS).
- An increase in the number of blocks (BLK) correlates with a rise in rebounds (REB). Typically, larger players are capable of both blocking shots and securing rebounds during the same possession.

On the other hand, negative correlations are observed:

- With an increase in the number of 3-point field goals made (3PTM), there's a decrease in offensive rebounds (OREB). Generally, players who excel at shooting and making 3-pointers are often smaller guards who don't frequently secure offensive rebounds.
- As the percentage of 3-point field goal attempts (3PTA) rises, the overall field goal percentage (FG%) decreases. This can be interpreted as the 3-point shot having a lower success rate due to its distance, thereby reducing the overall field goal percentage.
- An increase in the number of personal fouls (PF) leads to a decrease in minutes played (MIN). Each player can only commit six fouls per game before being fouled out, so the more fouls they commit, the fewer minutes they will play.

## How Are Minutes Distributed?
![newplot (3) (1) (1)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/d0d5c85d-6f93-4b28-a3fe-efcabd6db64b)

Taking a glance at the minutes distribution in the NBA, we notice that during the regular season, there's a more even distribution of minutes. Teams are inclined to experiment with different lineups and player combinations in pursuit of victories.

While both graphs exhibit right-skewed distributions, the skewness is more pronounced during the playoffs. Teams tend to rely heavily on star players and proven lineups, leading to a less evenly distributed graph and a higher percentage of players with fewer than 100 minutes played.

These observations are clearly illustrated in the third graphic, where the data output is converted to minutes per 48 minutes instead of total minutes played. By overlaying the regular season minutes distribution with the playoffs minutes distribution, we can discern a significant increase in the percentage of players logging upwards of 35 minutes during the playoffs compared to the regular season.

## Points Distribution
![newplot (6)](https://github.com/andychn10/NBA-Data-Project/assets/137304001/89cdf040-87a6-4bb0-b09b-047cff6d1a2a)
Examining the graph above, we notice an extremely right-skewed histogram, suggesting that over the past decade, the NBA has maintained a heavy reliance on its star players to generate high scoring outputs. This trend becomes even more pronounced during the playoffs, as evidenced by the orange histogram overlapping and extending beyond the blue histogram representing the regular season.

During the playoffs, there's a notable increase in the percentage of players averaging 20 or more points per game compared to the regular season. Additionally, there's a greater proportion of players scoring between 0 and 2 points per game. These findings point towards a tighter rotation among NBA teams in the playoffs, as they lean more heavily on key players to provide scoring for their respective teams.

# How has the game changed over the past 10 years?
## Analyzing Statistics Per 48 Minutes For A Given Team

![Pace, FGA, AST, AST-TOV](https://github.com/andychn10/NBA-Data-Project/assets/137304001/fb2bf51d-07ca-478d-b3e0-c245558fd7c7)

Analyzing the trends of the past decade in the NBA, one of the most notable changes is the acceleration of the game's pace. A key indicator of this evolution is the substantial increase in possessions and field goals attempted (FGA). As teams adopt a faster tempo, they often forego utilizing the full 24-second shot clock, instead favoring quicker scoring opportunities, which results in more frequent shot attempts and turnovers.

Another significant factor contributing to the increased pace is assists. Between 2012 and 2022, there was a notable uptick of 3.2 assists per 48 minutes. Assists serve as a barometer for the pace of play since they indicate easier scoring opportunities in transition and fast breaks, leading to more assist opportunities. Supporting this argument is the assists-to-turnover ratio, which shows a stark upward trajectory during the same period. This trend suggests fewer turnovers and more assists per 48 minutes, aligning with the notion of teams capitalizing on transition opportunities for easier scoring chances and fewer turnovers.

![3PM, 3PA, 3PA%](https://github.com/andychn10/NBA-Data-Project/assets/137304001/f4bdfe95-49e8-4c32-a5ae-59b16b6706f8)

The 3-point shot has undergone a dramatic transformation in the NBA, profoundly altering the game. Over the past decade, both the number of attempted and made 3-point field goals have surged. In 2012, NBA teams averaged around 20 attempts per game, whereas today, it's not uncommon for star players alone to attempt 10 to 15 3-point shots, with teams collectively averaging about 34 attempts per game.

All three graphs exhibit a consistent upward trend over the years, with the third graph specifically highlighting the proportion of attempted 3-point shots relative to all field goals in a single game. This particular graphic serves as a compelling indicator of how the 
3-point shot has reshaped basketball. Whereas scoring predominantly stemmed from 2-point field goals in the past, current NBA teams heavily rely on 3-pointers to generate the majority of their scoring, often accounting for at least 40% of their total shot attempts.

![TRU%, PT-FGA, 3PM-FGM](https://github.com/andychn10/NBA-Data-Project/assets/137304001/24a84df8-81c2-4a60-9a7d-48b817c02d62)

Finally, over the past decade, the level of talent and scoring prowess in the NBA has experienced substantial advancement. Players have become notably more efficient scorers, capable of producing higher scoring outputs.

The true shooting metric serves as a comprehensive basketball statistic that offers a more nuanced measure of shooting efficiency. It takes into account field goals, free throws, and three-point shots, thereby providing a holistic assessment of a player's scoring proficiency. The formula for true shooting percentage is as follows:

![True Shooting Formula](https://github.com/andychn10/NBA-Data-Project/assets/137304001/1d3f8990-aabf-4f3d-991f-d3b44bf7a2c0)

It is considered a more accurate representation of a player's scoring efficiency compared to traditional field goal percentage because it incorporates the value of three-point shots and free throws.

When analyzing the points per field goal attempts metric, we observe an upward trend, indicating that players are scoring more efficiently and making more three-point field goals. This is noteworthy considering that three-point shots are theoretically more challenging compared to two-point field goals due to their distance from the basket. This assertion finds support in the third graphic, which illustrates an increase in the ratio of three-point field goals made to total field goals made.

