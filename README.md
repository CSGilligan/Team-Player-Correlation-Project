# Team-Player-Correlation-Project
 
With this project, I am aiming to find a correlation between player success and team success on the MLB's Boston Red Sox, to create a stat called TPC (Team-Player Correlation). The idea is to show which Red Sox players' success has correlated most strongly with the team's win rate. This may help us think about 'value' differently when we consider who are the most valuable players.

I built a scraper to pull data from baseball-reference.com to pull each player's page from the team page. From those player page urls, I built the urls for each player's game log page, where data from each game is available. From there, I pulled the data from the game-by-game tables and manipulated it to:
    a) reassign the team result column as 1 for a win and 0 for a loss,
    b) create a new column to show the player's OPS in each game, and
    c) find the correlation between these two
    
At this moment, the scraper is built and the analysis shows a variety of TPCs among Red Sox role players, which I've visualized here: https://datawrapper.dwcdn.net/8ddJd/1/

I'm hoping to do much more with this, including expanding it to a league-wide analysis, but this is as far as I've gotten now!