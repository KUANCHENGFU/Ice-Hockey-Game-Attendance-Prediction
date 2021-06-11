# Ice Hoceky Game Attenddance Prediction

## Overview
Imagine that the VP of Ticket Sales asks you to predict our attendance for next season and use this information to sort our games into tier levels based on demand. Therefore, the purpose of this project is to develop a reliable framework which is capable of predicting attendance for the upcoming season's home games and placing them into tiers. The project is composed of below parts: feature preprocessing, feature engineering, model building, hyperparameter tuning, model evaluation, feature importance, and attendance prediction.

The distribution of attendance from the 14-15 season to the 19-20 season shows that the number of games at full capacity is about half of the total number of games, which indicates there is a imbalanced problem for regression. Therefore, a two-layer model is proposed to solve this problem. In short, a random forest classifier is first used to predict whether a given game will be at full capacity and then a k-NN regressor is applied to estimate the given game’s attendance if it will not be at full capacity.


## Link to the Project
1. https://nbviewer.jupyter.org/github/KUANCHENGFU/Ice-Hoceky-Game-Attenddance-Prediction/blob/main/Ice_hoceky_game_attenddance_prediction.ipynb
