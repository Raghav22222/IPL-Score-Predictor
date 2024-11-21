# IPL-Score-Predictor
It is a Machine learning algorithm which predicts the first innings score based on some parameters with 92% accuracies
Algorithms used:

Linear Regression
K-Nearest Neighbor Regressor
XGBoost Regressor
RandomForest Regressor
SVR
Decision Tree Regressor
Dataset:

The dataset comprises of over by over details of matches and runs from 2008 to 2020 in the updated file and the rest data from 2020 to 2023 is in the second csv file.

Dataset Used: ipl_data.csv

mid - match id
date - when matches are played
venue - place where matches aew played
bat_team - batting team
bowl_team - bowling team
batsman - batsman
bowler - bowler
runs - runs scored
wickets - wickets
overs - overs - next 3 are based on this
run_last_5 - runs scored in last 5 overs
wicket_last_5 - wickets in last 5 overs
stricker - batsman playing as main 1
non-striker - batsman playing as runner up - not main 0
total - total score (target variable)

Some sucessfull predictions are :
![image](https://github.com/user-attachments/assets/2408363f-f7c7-400c-9f6e-aa0ddabe466e)

above image is the model testing stage where the final between Sunrisers and Kolkata was played in 2024 and you can see the Predicted Score is 115 and the Actual was 114.
