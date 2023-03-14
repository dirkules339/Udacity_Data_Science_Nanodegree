# Libraries
- pandas
- numpy 
- matplotlib
- seaborn 
- sklearn.linear_model 
- sklearn.metrics 
- sklearn.model_selection 
- sklearn.preprocessing 

# Motivation
I'm a soccer fan and am interessted in understanding the marked value of soccer players and if it ist possible to predict the value.

# Files in repository
- appearances.csv: information about goals, cards and minutes played per player and game
- club_games.csv: Information about the games (results etc.)
- clubs.csv: List of clubs including info about which leagues they play in
- competitions.csv: which leagues aund competitions are included
- game_events.csv: Information about what happens during the games
- games.csv: information about games, which clubs played against each other in witch competition and what was the result
- player_valuations.csv: market value of players by date
- players.csv: Information about the player like name, club he plays for, market value etc.

# Results
It was possible to use linear regression model to predict the market value of players, but the R2 was quite bad. by including more features the r2 could be dobled but to get a goog usable model more "good" features are needed.
