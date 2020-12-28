# BaseBall Wins Prediction using ML Algorithms -Moneyball Dataset-

# Context:
In the early 2000s, Billy Beane and Paul DePodesta worked for the Oakland Athletics. While there, they literally changed the game of baseball. This data set contains a set of variables that Beane and DePodesta focused heavily on.
They determined that stats like on-base percentage (OBP) and slugging percentage (SLG) were very important when it came to scoring runs, however they were largely undervalued by most scouts at the time. Since these players weren’t being looked at by other teams, they could recruit these players on a small budget.

# Columns in the dataset:
> Team
> League
> Year
> Runs Scored (RS)
> Runs Allowed (RA)
> Wins (W)
> On-Base Percentage (OBP)
> Slugging Percentage (SLG)
> Batting Average (BA)
> Playoffs (binary)
> RankSeason
> RankPlayoffs
> Games Played (G)
> Opponent On-Base Percentage (OOBP)
> Opponent Slugging Percentage (OSLG)

# Objective:
The objective here is to predict the number of wins by a team for the year 2002 by analyzing the game stats for the years from 1962–2001.
Note: The number of wins recorded by the team in the year 2002 was 103. The idea is to replicate the data analysis done in the year 2001 with the latest ML models and check if we can get the prediction close to 103. Hence, I will be using the 4 features that were used in 2001 for this task.

## Model Predictions

The Oakland Athletics statistics in 2001 before the playoffs.

OBP: 0.339

SLG: 0.430

OOBP: 0.307

OSLG: 0.373

Created test record with these values and then using models to generate predictions.


