# Fantasy Hockey Analysis

<hr>

# Background
I built this notebook with the intent of maximizing my chances of winning my Fantasy hockey league using some simple linear regression modeling to estimate future performance based on the past years' performance.

# Objective
Analyzing NHL player and goalie data to optimize fantasy hockey draft performance to maximize expected value.

# Methodology
The plan will be to use various performance data from the previous year and forecast each performance metric of the subsequent year individually. When all modeled player/goalie performance metrics are predicted, the fantasy points will be calculated based on the Fantasy league's system. This will also be done on a per game basis as injuries have a large impact on the overall points expected from players going from year to year.

The optimization of player/goalie selection will mostly be based on a per game basis with some acknowledgement of games played in the previous year noting past injuries and missed games.

## Yahoo League Fantasy Scoring Format
<b>Roster</b>
* 12 players
* 1 goalies

<b>Player</b>

* Goals = 30 pts
* Assists = 25 pts
* +/- = 5 pts
* PIMs = 1 pt
* Powerplay Goal (PPG) = 5 pts
* Powerplay Assist (PPA) = 5 pts
* Shorthanded Goal (SHG) = 10 pts
* Shorthanded Assist (SHA) = 10 pts
* Game Winning Goal (GWG) = 5 pts
* Shots on Goal (SOG) = 1 pt
* Face-off Wins (FW) = 1 pt
* Face-off Losses (FL) = -1 pt
* Hits = 1 pt
* Blocked Shots = 1 pt

<b>Goalies</b>

* Wins = 35 pts
* Saves = 2.5 pts
* Goals Against = -15 pts
* Shutouts = 25 pts

<hr>

# Data Source
Data gathered from <a href="https://www.hockey-reference.com/">hockey-reference.com</a>
