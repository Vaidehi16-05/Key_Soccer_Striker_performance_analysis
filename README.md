# Key_Soccer_Striker_performance_analysis
As a group of data analysts, we have been hired by the 'World Soccer' sports magazine.
Amid the thrilling matches of the FIFA World Cup, the management wants us to release a detailed report on Cristiano Ronaldo using data driven insights to attract and engage the audience

Our main objectives for this project:

    1. How has Manchester United's performance been over the last 20 years and how has Ronaldo been a huge contribution.
    
    2. Determine how playing matches on the home ground affected the winni-ng probability for Manchester Untited during the period where Ronaldo  played for them  vs the period he did not.
    
    We are interested in analysing how Ronaldo's performance boosted Manchester United's winning probability when was playing at the home ground. We will  be comparing the percentages between (2003-2009) and remaining seasons data for the club as a metric to add value.
    
    3. What does the trajectory of Ronaldo's career look like?
   
    4. Drilling down to one his best performances in a season i.e 2017/18  for Real Madrid, we try to analyse the pattern of how he scores goals.
 
<h3> Detailed description of the data set(s) and how they were acquired:</h3>


<h5>1. Premier league matches Dataset </h5>

https://www.kaggle.com/datasets/evangower/premier-league-matches-19922022 

This dataset acquired from Kaggle includes every game ever played in the English Premier League, starting in 1992 and continuing through the last week of the 2021–2022 season. Each season lasts for 1 year, and a total of 20 teams compete in the competition.

<h5>2. Manchester United Club's achievements Dataset</h5>

https://en.wikipedia.org/wiki/List_of_Manchester_United_F.C._seasons

This webpage lists the details of the Manchester United club's achievements in major competitions for all years from its inception. We will use information in the 'Results of league and cup competitions by season' table to identify in which seasons the club has won the premier league title.

<h5>3. Match Events Dataset - Player, Time, Outcome, Position details</h5>

https://www.nature.com/articles/s41597-019-0247-7

Public dataset that contains spatio-temporal match events that had occurred during football match.Each of the match event consists of information about its position, time, outcome, player and characteristics. We downloaded a JSON file which was read converted to a pandas dataframe for analysis.


<h5>4. Ronaldo's Club goals dataset</h5>

https://www.kaggle.com/datasets/azminetoushikwasi/cr7-cristiano-ronaldo-all-club-goals-stats

This dataset acquired from Kaggle consists of the complete list of all club goals of Ronaldo. CSV file was used for processing and analysis.

<h5>5. Dataset with other Player details</h5>

https://www.kaggle.com/datasets/tanujleomessi/ligue1topscorer

This dataset acquired from Kaggle has player's details who have the potential to replace Ronaldo.

<h5>6. Dataset with other players biography information</h5>

https://www.kaggle.com/datasets/cashncarry/fifa-23-complete-player-dataset

This dataset acquired from Kaggle has the player's biography information like age, weight, height, sprinting speed, etc.
