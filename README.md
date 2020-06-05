# IDAgroupAssessment

Methodology - 

The main objective of the analysis conducted for the cricket dataset is to select an all-time best eleven cricket team. The data is extracted from ESPN CricInfo and this makes our data reliable and legitimate. The data had some inconsistencies with Player names sometimes having their country along with names. These inconsistencies were removed by defining a function with Regular Expression that filtered out only the player names. 

The first and foremost decision to be made for player selection is to choose the specific quantifiable variables based on which the Players are selected. Some of the variables used for this were simple stats of the players. There is a bias observed in the data with some players having played more matches than others. This would mean that they have better stats compared to someone who has played lesser matches. By calculating some mathematical formulae, this bias was compensated for and made more fair for all players by using Net Performance as a decision factor. This makes our analysis more effective.

The other problem faced with this approach was that players with very less matches had far better Net Performance than players who have played more matches. This was solved simply by defining the minimum number of matches a player must have played for the analysis.

Once these selected players are plotted interactively, it is just a matter of picking the players with the best desirable values of the variables. It is not ideal for some variables to have  high values. For example, the economy of a bowler should be ideally low since this variable measures the number of runs conceded by a bowler. Fifteen Members are picked from the entire dataset to be analysed further to see if the picks have the desired measures of the variables.

The individual player analysis compares all the players in each specific activity such as batting, bowling, wicket-keeping and also a variable that measures the ability of a player to captain his side. After conducting these analyses, the all-time best eleven cricket team along with substitutes is selected.  