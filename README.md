## CMPE297_AdvanceDL_Project
# Stock Options Prediction with Advanced Deep Learning

https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/title.png
## Members:
* Jacky
* Jerry
* Jumana

## Proposal
[!image]https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/Stock%20Options_Project_Proposal.pdf
In the investment terms options is a derivative which is derived from the price of
another security. Another security can be a stock, a currency, rate or a commodity. This
means that the price of options moves if the price of another security would move.
Understanding how options are priced is important because there are a lot of variables
that determine its value.

In this project we are creating a Deep Learning model for the prediction of the
price of an option. Options prediction can help in determining the investment better and
understanding the stock marketing better. In our model, we pick specific options of the
stock. We need to consider the five important characteristics of the option
stock-Underlying asset, Call vs. put, Strike price, Expiration date, and American vs.
European. These five features are the input to our model and output of the model will be
the price. As we know there are many different strategies for options trading depending
on what we want to get and how much risk we are willing to expound, we will limit the
features for the scope of this project.


## Data Preprocessing and Crawler 
-https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/tree/main/Data_Preprocessing
## Models and Results 
-https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/tree/main/models

## Project Report and PPT presentation 
- https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/tree/main/Documentation
### slides
https://docs.google.com/presentation/d/1TLyDg_THqW6SLe9ueSo-tYWTkLsFwSMV6-OCWgZKhY0/edit?usp=sharing
### report

## Colabs, Datasets, Saved models
- Google Drive


## Future Work

* Stocks filter — Using the stocks with better Sharpe Rate 
* Option filter
  -- Not using the options deep out of the money(The Deep-OTM options are more volatile)
  -- Not using the options expired in 7 days (The options closer to the expiry date are more volatile) 
* More models, More data, More training, More metric
* Apply to the real trading
* Fine-tuning with more hyperparameters
