# ORIE 4741 Project Proposal: Predicting NFL Game Outcomes
## Group Members: Rohan Lewis (rl447), Matthew Armstrong (msa225), Michael Nercessian (mn487)


### **Question**
Our goal is to predict the winner and point differential of NFL games based on historical season, game, and player data.

### **Datasets**
[Season and game data](https://www.pro-football-reference.com/years/2019/opp.htm)

[Play by Play Data 1](https://github.com/ryurko/nflscrapR-data/blob/master/play_by_play_data/regular_season/reg_pbp_2019.csv)

[Play by Play Data 2](https://github.com/ryurko/nflscrapR-data)

So far we have three different groups of football data we are working with: all play-by-play data, season offense/defense data (passing yard avg, total tackles, total sacks, etc.), and weekly game data (point scored, field goals made, touchdowns made, third downs converted, etc.). We will need to determine the most relevant features that will be most important to develop the model as well as find appropriate weights for these variables in order to optimize our outcome. We will start by cleaning up all of the data for analysis before deciding which statistical models will be most appropriate to best predict the winner and point differentials of a football game. In order for our model to be considered effective, it would need to predict football game spreads with a minimum of 55% accuracy, so this will be our outcome goal. For simple win/lose prediction we would like to see our model predict at least 75% of games correctly. 

### **Project Value**
This model will provide a valuable tool for interested fans and to the legal sports gambling industry. By creating a model that can accurately predict point differentials, we can introduce a model that can potentially beat betting lines consistently. Betting lines are designed to attract equal money to either side of the line; they are a proxy but not necessarily a prediction for point differential in a game. If our model can more accurately predict point differentials than the proxy set forth by betting lines, we could potentially introduce an incredibly valuable tool to sports gambling.
