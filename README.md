# IPL_SCORE_PREDICTION

## AIM:
    To predict the IPL score using Machine Learning.		
## DATASET:
    The data set can be downloaded here: https://www.kaggle.com/yuvrajdagur/ipl-dataset-season-2008-to-2017


## DATASET FEATURES:
* mid: Unique match id.

* date: Date on which the match was played.

* venue: Stadium where match was played.

* battingteam: Batting team name.

* bowlingteam: Bowling team name.

* batsman: Batsman who faced that particular ball.

* bowler: Bowler who bowled that particular ball.

* runs: Runs scored by team till that point of instance.

* wickets: Number of Wickets fallen of the team till that point of instance.

* overs: Number of Overs bowled till that point of instance.

* runslast5: Runs scored in previous 5 overs.

* wicketslast5: Number of Wickets that fell in previous 5 overs.

* striker: max(runs scored by striker, runs scored by non-striker).

* non-striker: min(runs scored by striker, runs scored by non-striker).

* total: Total runs scored by batting team at the end of first innings

* date: Date on which the match was played.

* venue: Stadium where match was played.

* battingteam: Batting team name.

* bowlingteam: Bowling team name.

* batsman: Batsman who faced that particular ball.

* bowler: Bowler who bowled that particular ball.

* runs: Runs scored by team till that point of instance.

* wickets: Number of Wickets fallen of the team till that point of instance.

* overs: Number of Overs bowled till that point of instance.

* runslast5: Runs scored in previous 5 overs.

* wicketslast5: Number of Wickets that fell in previous 5 overs.

* striker: max(runs scored by striker, runs scored by non-striker).

* non-striker: min(runs scored by striker, runs scored by non-striker).

* total: Total runs scored by batting team at the end of first innings
    
## MODELS:

  *  Linear Regression
  
  *	Lasso Regression 
  
  *	Decision Tree
  
  *	Random Forest
  
  * Boosting using decision trees
  
  *	SVM Regression
  
  *	MLP Regressor(Neural Network)
  
## THE BEST MODEL:
   * The model with the best score was Random Forest.
   * If your aim is to have a faster fitting of the model then use Decision trees as it is much faster with a pretty decent score.
   * Neural network(MLP regressor) will give better results if had much more data but fitting the neural network is time consuming.
