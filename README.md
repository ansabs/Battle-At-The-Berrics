# Battle At The Berrics Competition Analysis
A statistical analysis of the annual Battle At The Berrics competition.

In this project, I analyzed various aspects of the annual Battle at the Berrics competition, hosted by Berrics. The competition is tournament style, where each match is a game of S.K.A.T.E. Similar to the basketball game H.O.R.S.E., “Roshambo” (rock, paper, scissors) is played to see who sets first (who is on offense). The setter does a trick, and then the defender must repeat the trick. If the defender misses, they get a letter. If the setter misses, it is the other player’s turn to set. The first person to get five letters loses the game.  
## Data
The dataset I used is the [Battle at the Berrics API](https://api.batbstats.trevorblades.com/), developed by skater Trevor Blades. The data was transcribed by Andrew Jones from the Battle at the Berrics YouTube videos. Because the videos are public, no data was taken without consent by Blades and Jones. It is important to consider that the data was transcribed by a third party, meaning transcription errors were possible. The data also represents professional skaters, not the general skateboarding community. To actually extract the data from the API, I needed to use a GraphQL query on the API’s website, and then use CURL to turn this data into a JSON file.  
## Analyses
Trick Consistency - Which tricks are successfully landed the most consistently?
Trick Variation Distribution - What trick variations are the most popular, and what is the make rate for each one?
Roshambo - Does winning roshambo (RPS) give you better odds of winning the match?
Trick Popularity vs. Make Rate Regression - How does the attempt count of a trick relate to its make rate?
Logistic Regression Model To Predict Match Outcomes - Can we create a logistic regression model to predict who will win a game of S.K.A.T.E. between two skaters?

## Credits
Trevor Blades
Andrew Jones
Rush Sanghrajka
