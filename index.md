![Summary Figure](/images/Fantasy_Football_ML_summary_figure.jpg)
## Introduction

The goal of this project is to accurately predict fantasy football performance for NFL wide receivers on a game-to-game basis. Performance is calculated via points that can be earned by a player for accumulating yards gained, touchdowns scored, or passes caught. Similarly, points can be lost by a player for losing yards or fumbling the ball. At the end of every game, a player's total points are tallied, and the player with the highest number of points has the most value for that game.

Players of *fantasy* football, users, will select a roster of players every week in an attempt to accumulate the highest sum of points via their roster. Users will use a variety of information to make an informed decision on their roster selection. Typical facets of information include previous player performance, player matchups, scouting reports, and projected points. From personal experience, most players tend to lean towards projected points as the main indicator for their analysis.

Player performance is typically calculated through sentiment analysis and season simulation adjusted for defensive pairings<sup>1</sup>. However, we will be taking a different approach to our player performance projections in order to eliminate the sentiment factor which could contribute bias to the model. We will be strictly using a player's matchup and statistics such as height, strength, speed, and prior performance. In addition, we will attempt to group similar style players and defenses together to help aid in our predictive model. 


## Methods
We are going to use a database found on Kaggle that reports the statistics of wide receivers for the 2014, 2015, and 2016. We will use these statistics to evaluate the Football Fantasy performance. We will use Random Forest, Decision Tree, and SVM for our machine learning algorithms. We will use the 2014 and 2015 statistics to train our data. Then, we will compare our machine learning predictions against the actual Fantasy performance of the wide receivers for the 2016 season. 

## Results

## Discussion

## References