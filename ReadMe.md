
# Business Understanding

A Local Casino wants to know if I can create a model that can correctly recommend whether or not they should place a bet on the over/under or 'Total' line in an NFL football game.

This would be beneficial to the casino because they are currently losing money placing bets on the over/under the line and losing their bets

Typically a Casino, wants the bet count to be even (the same amount of people bet for both outcomes) so they can take a small percentage back for providing the bet. Alternatively, they want to have most people be on the losing end of the bet so the casino would be able to pay itself from the losing betters.

Many people have noticed when they bet the score will be 'over' score AND the home team is the favorite to win they come out on top. 

This causes the Casino to decrease in revenue, as everyone is placing a bet on the same things and most of the time they are winning which causes the casino to have to pay the customers directly and not from the bets of other people who have lost. 

The Casino has contacted me to review a model that can be created that can correctly predict/ the over underline in an NFL Games 




### The Nuts and Bolts of an Over_Under Bet
When looking at listed odds for a game, this is represented as total, over/under, and sometimes shortened as O/U. There will be a number listed, something like 155 for a college basketball game, 8 for a baseball game, or 47 for an NFL game. That number is the line for over/under bets, called the total.

A bet on the over means you think both teams will combine to score more goals, points, or runs than the total listed. Conversely, an under bet means you think there will be less than the total listed. It’s that simple.
 
 
[More Information About Sports Betting](https://theathletic.com/2523188/2022/01/25/what-is-the-over-under-in-sports-betting/#:~:text=A%20bet%20on%20the%20over,It's%20that%20simple.)


The question to be answered is there a model that offers a statistical advantage to betting the over when the home team is the favorite to win the game

Null Hypothesis:

There is a model that can offer accurate picks of the over/under line 

Alternative: Hypothesis

there is not a model that can offer accurate picks of the over/under line 


Metrics used To compare models we will focus on 1 major metric:
F1-Score

### Objective
We want to create a model that  predicts that the over/under pick allows the casino to alter the bets being mad and conjure more revenue 
 
#### Model Types Used
- Logistic Regrssion (Baseline)
- Decision Tree 
- Random Forest Classifier
- Gradient Boosting 


## Conclusion


Final Modeling Results

Final model selected were evaluated with the additional feature and on the a quantile scaler it is important to note that the predictions and coefficients of the model could be wrong

Top performing model is the Random Forest classifier


### F1 - Score : 0.88
### RMSE - Score: 0.10
 
