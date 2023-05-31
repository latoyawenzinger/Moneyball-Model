# Moneyball-Model

## Project Idea: Money Ball 
-	Book: Moneyball - The Art of Winning an Unfair Game, written by Michael Lewis (2003) - The Oakland Athletics baseball team and its general manager Billy Beane assemble a competitive baseball team despite Oakland's small budget; Its focus is the team's analytical, evidence-based, sabermetric approach.
-	Film released in 2011

## Project Description/Outline:
The goal of this project is to build the best team on the lowest budget via machine learning. A tableau dashboard will help to visualize how the machine learned team holds up against the actual MLB league. [CLICK HERE](https://public.tableau.com/app/profile/latoya.wenzinger/viz/Moneyball_16852168288720/MoneyballThePriceisRight) to view our Moneyball data dashboard!
	
## Datasets to Be Used:
1.	[**Spotrac.com MLB 2022 Salary Data**](https://www.spotrac.com/mlb/payroll/2022/)
2.	[**Batting Data**](https://www.kaggle.com/datasets/vivovinco/2022-mlb-player-stats?q=MLB+in%3Adatasets&select=2022+MLB+Player+Stats+-+Batting.csv)
3.	[**Pitching Data**](https://www.kaggle.com/datasets/vivovinco/2022-mlb-player-stats?q=MLB+in%3Adatasets&select=2022+MLB+Player+Stats+-+Pitching.csv)


**MONEYBALL Analytics Project**
Machine Learning Project using 2 key offensive and pitching metrics to assemble the best fantasy lineup possible with a budget of $75 Million. Results of 2022 player analysis will be compared to real world results for the 2023 season and also compared to simulations completed using the video game MLB The Show 23 for some extra insights into our results.

*If Starting Pitching appearances do not match up to formula numbers will be prorated
**If Relief Pitchers do not have 81 IP, numbers will be prorated
***All batting statistics will be matched up to formulas as required
****Extra Inning games have been factored into our relief pitching inning counts

Analytics constraints:
Team Budget $75 Million
Statistics from 2022 Season
Player salaries for budget from 2022 Season
Machine Learning methods used to create team based on performance v. budget

Moneyball player formulas

Starting Outfielders Multipliers (4) ($15 Million)
3 players 145 Games
1 reserve player 51 Games

Infielders (6) ($15 Million)
4 players 140 Games
2 reserve players (44 games each)

Catchers (2) ($7 Million)
1 player 115 Games
1 reserve 47 Games

Starting Pitchers (5) ($23 Million)
2 players 33 games, 3 players 32 Games (6 Innings per game)

Relief Pitchers (8) ($15 Million)
8 players (3* Innings per game)
    4 Innings x 162 games = 648 IP or 81 IP per player(*Accounts for Extra Innings)

Areas of Interest from an offensive perspective
OBP (statistic tracking percentage of plate appearances resulting in walks or hits) and 
OBPS (statistic including On-Base Percentage and Total Bases collected per hit)

Areas of Interest from a Pitching perspective
ERA or Earned Run Average (9 * ER/IP)
WHIP or Walks/Hits per Innings Pitched (Stat will be taken as is)

## **Rough Breakdown of the Tasks:**
- Ulrich - Simulation software to see how effective the machine learning model is
- Mateus - Machine Learning of Pitcher data 
- Candy - Machine Learning of Batting data
- Latoya - Tableau Dashboard

## **Resources**
- [Dashboard background](https://wall.alphacoders.com/big.php?i=584499)
- [MLB logo](https://en.wikipedia.org/wiki/Major_League_Baseball_logo)
- [Batting/Pitching Stats](https://www.baseball-reference.com/leagues/majors/2023.shtml)
- [Payroll](https://www.spotrac.com/mlb/payroll/2022/)
