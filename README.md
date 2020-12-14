# Research of football clubs wins

This notebook answers a question:
* How have the win percentages for the four major Moscow football teams change over the last thirty years?
* What place took each team in every year?

## Data

All data was taken from:
  https://www.transfermarkt.ru/Премьер-лига/ewigeTabelle/wettbewerb/RU1/plus/?saison_id_von=2020&saison_id_bis=2020&tabellenart=alle
  
File `teams.xlsx` contains data of 4 Moscow football teams:
* FC CSKA 
* FC Lokomotiv	 
* FC Spartak 
* FC Dynamo

Observation period from 1991 to 2019. We received data about:
* Number of wins
* Number of draws
* Number of loses
* Number of points
* Place in each year

## Plotting

This visualization was concerned with answering the question of how the win percentages of the four
major Moscow football teams (FC CSKA, FC Lokomotiv, FC Spartak, FC Dynamo) have changed over the last 30 years. Link data was scraped for data concerning wins, draws, losses and points by season for each team. A graph for almost 30-year period was plotted to help the reader identify any major trends in the team’s win percentages.

## Interactive

Also was plotted interactive graph. You can see it in source code. By clicking a line on it you can see what place a current football club took in current year.
