

![losing%20money.jpg](attachment:losing%20money.jpg) additional





# Business Understanding

A Local Casino wants to know if a can create a model that can correctly reccomend whether or not the should place a bet on the the over/under or 'Total' line in a NFL football game.

this would be beneficial to the casino because they are currently losing money placing bets on the over/under line and losing there own bets

Typically a Casino, wants the bet count to be even (same amount of people bet for both outcomes) so they can take a small percentage back for providing the bet. Alternatively they want to have most people be on the losing end of the bet so the casino would be able to pay itself from the losing betters.

Many people have noticed when they bet the score will be 'over' score AND the home team is the favorite to win they come out on top. 

This causes the Casino to decrease in revenue, as everyone is placing a bet on the same things and most of the time they are winning which causes the casino to have to pay the customers directly and not from the bets of other people who have lost. 

The Casino has contacted me to ensure a model can be created that can correctly predict/ the over under line in an NFL Games 





### The Nuts and Bolts of an Over_Under Bet
When looking at listed odds for a game, this is represented as total, over/under, and sometimes shortened as O/U. There will be a number listed, something like 155 for a college basketball game, 8 for a baseball game, or 47 for an NFL game. That number is the line for over/under bets, called the total.

A bet on the over means you think both teams will combine to score more goals, points, or runs than the total listed. Conversely, an under bet means you think there will be less than the total listed. It’s that simple.
 
 
[More Information About Sports Betting](https://theathletic.com/2523188/2022/01/25/what-is-the-over-under-in-sports-betting/#:~:text=A%20bet%20on%20the%20over,It's%20that%20simple.)


### Why is this important? 
 An estimated 45.2 million Americans plan to wager on the NFL season in some form, up 36% from last year, according to research from the American Gaming Association. At least 

12 billion will be bet on the NFL this season, according to sports betting market tracker PlayUSA.

[NFL BETTING STATICS](https://www.cnbc.com/2021/09/09/more-americans-will-wager-on-the-nfl-as-the-league-embraces-betting.html)

As the bets increase there is more potential for revenue in the point spread stye of betting. 

______________________________________________________________________________________________________________________


The question to be answered is there a model that offers a statistical advantage to betting the over when the home team is the favorite to win the game

Null Hypothesis:

There is a model that can offer accurate picks of the over/under line if the home team is the favorite

Alternative: Hypothesis

there is not a model that can offer accurate picks of the over/under line if the home team is the favorite 


Metrics used To compare models we will focus on 1 major metrics:
F1-Score
which takes both precision and recall into account to ultimately measure the accuracy of the model. The reason this metric was choosen is because while true negatives are often less important to what ever problem you’re trying to solve especially in a business setting. 

The F1 score tries to take this into account, giving more weight to false negatives and false positives while not letting large numbers of true negatives influence your score. 
 
 great article going into the metrics found [here:](https://towardsdatascience.com/whats-the-deal-with-accuracy-precision-recall-and-f1-f5d8b4db1021)


### Objective
We Want to create a model that correctly predicts that the over/under pick allowing the casino to alter the bets being mad and conjure more revenue 
 
 
 
 ![Home%20Win%20Distrubution.JPG](attachment:Home%20Win%20Distrubution.JPG)
 
 
 ## Conclusion


Final Modeling Results

Final model selected were evaluated with the additional feature and on the a quantile scaler it is important to note that the predictions and coefficients of the model could be wrong

Top performing model is the Random Forest classifier


### F1 - Score : 0.88
### RMSE - Score: 0.10
 
