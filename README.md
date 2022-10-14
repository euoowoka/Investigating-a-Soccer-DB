
## by Emmanuel Owoka


## Dataset

> The dataset analysed here is the soccer database which contains information on soccer matches, soccer players, and teams from several European countries from the year 2008 to 2016.

The soccer database contains six(6) tables named Player_Attributes, Player, Match, League, Country, Team, and Team_Attributes.

The Player_Attributes contains the rating of individual player's abilities over the seasons which is linked with the Player table, by the attribute player_api_id and player_fifa_api_id, which contains basic information of a player.

The Match table contains the statistics of games playes from the 2007/2008 season to the 2015/2016 season of selected European leagues. The Match table is linked to the Player_Attributes, Player, League, Country, Team, and Team_Attributes.

The League table contains the name of the top flight leagues in select countries in Europe.

The Country table contains the name of countries of the leagues.

The Team table contains the name of the teams in the selected leagues.

The Team_Attributes contains the abilities of the individual teams in different seasons.

Due to the large number of columns, the columns found in the different tables would be seen in the next session.

The data source used in this study is an sqlite file, which is an sql database. Therefore, sql queries would be ran tooperate on the tables in the database.

The major aim of this study is to find out what team and league has the most goals scored. To achieve this, the Match table will joined with the team and league tables to get the goals scored by a team or league. Then, the result will be communicated using a bar plot.


## Research Questions

Research Question 1 (Does the height of a goal keeper affect the overall rating of the keeper?)
Research Question 2 (Do tall players have a high heading accuracy?
Research Question 3 (Does the weight of a player affect the speed of the player ?)
Research Question 4 (What team has the most goals the 2015/2016 season in each league?)
Research Question 5 (What league has the average highest scored goals ?)

