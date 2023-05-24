# CS5265-Repo
Repo to host assignments from CS5265 - Foundations of Machine Learning Course

# Week 2 Updates

//Should include reference to business metrics such as cost/revenue etc. perhaps this shstem could be useful in professional sports management. How much money does a win or loss represent? This may also be useful for a business that manages online bets. Odds calculated based on this type of system could save the "house" quite a bit from unexpected payouts, perhaps. RH

#Intro
According to Front Office Sports (https://frontofficesports.com/sports-betting-industry-record-7-5b-2022-revenue/#:~:text=Commercial%20sports%20betting%20revenue%20hit,from%20the%20American%20Gaming%20Association), the sports betting market generates $7.5 Billion dollars each year and that number seems to keep growing. Needless to say there is a gold mine for those who can predict sports outcomes best and loads of potential careers as developers for companies that manage online bets such as FanDuel, BetMGM and DraftKings

## Confusion Table
| | Team A Wins | Team A Losses |
| ------------- |:-------------:| -----:|
| Predict Team A Win | True Positive | False Positive |
| Predict Team A Loss | False Negative | True Negative|

For my project, I will be working on creating a model capable of predicting NFL game results. All my data is publically accessable through the NFL's API and I will be using a dataset provided by FiveThirtyEight (https://data.fivethirtyeight.com/) so there is no cost to calculate or scrape the data. 

My above confusion table is fairly simple, a true positive is predicting team A wins correctly, a true negative is predicting a loss correctly and false results are included as well.

If I can reach a model that can predict games about 60% of the time properly, I will consider the model a success. If the model ends up predicting the incorrect winner, that would be the "error" case and would then drop the success rate.

//It may be a good idea to restate your error in the same sentence that you state the error goal of 60%. RH
