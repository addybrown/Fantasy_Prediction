Fantasy Prediction and Data Analysis for NBA Fantasy Season 

Note: Please Run Data Cleaning, Data Analysis, Model Notebooks in Sequential Order 

Basic Overview of Project: Built A ANN Regressor to predict Expected Fantasy PPG Output for 2018/2019 NBA Season 

Inputs for network were all advanced statistics and expected MPG. 
These statistics included VORP-Value Over Replacement Player
                          WS- Win Share
                          OWS-Offensive Win Share 
                          DWS-Defensive Win Share
                          PER- Player Efficiency Rating 
                          MPG- Minutes Per Game 
                          BPM-Box Plus Minus
                          OBPM-Offensive Box Plus Minus

The reason these advanced statistics were chosen were because they tended to have higher correlations then many of the other statistics 
The second reason advanced statistics were chosen is due to the fact that there is minimal variability on a per season basis as compared to many traditional statistics. Ultimately this model aims to find the diamond in the rough, or breakout player for my fantasy basketball league. 

The scoring is demonstrated in the Data Cleaning Jupyter Notebook. 


In the Data Analysis: The data is visualized.

To generated the predicted outputs for the 2018/2019 nba season probability distributions were created and random noise in-line with those probability distributions were added or subtracted to the players 2017/2018 statistics. Factors like players age/experience were also taken into account. For example there tends to be a large jump in player output from their 3rd to 4th nba season. 

The MSE, Mean Squared Error on the test data most updated: 0.977 (Quite good) for the projection of fantasy points per game. 

Data Cleaning---> Cleans raw Season Stats 
Data Analysis---> Analyses Data and generated the csv file for the 2018/2019 NBA projection 
Model-----------> Neural Network used to generate final predictions 


COMING SOON: Performance----> Will compare predictions vs actual results once season is complete to see how well model did. 
