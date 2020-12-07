## CMPE297_AdvanceDL_Project
# Stock Options Prediction with Advanced Deep Learning

![image]( https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/title.png)
## Members:
* Jacky
* Jerry
* Jumana

## Proposal
https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/Stock%20Options_Project_Proposal.pdf

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
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/LSTM_model.png)

![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/LSTM_result.png)

![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/Model3_result_Bid.png)

![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/Model3_result_Ask.png)


## Project Report and PPT presentation 
- https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/tree/main/Documentation
### slides
https://docs.google.com/presentation/d/1TLyDg_THqW6SLe9ueSo-tYWTkLsFwSMV6-OCWgZKhY0/edit?usp=sharing
### report

## Training process

![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/LSTM_tensorboard.png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/model2_call_WIX.png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/model2_put_all%EF%BC%88n400_batch1024_eposhs2400_lr1e-5\).png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/model3_call_all%EF%BC%88n400_batch1024_eposhs2000_lr1e-5\).png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/model3_call_all%EF%BC%88n400_batch1024_eposhs2000_lr1e-5\).png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/model3_sigma5.png)
![image](https://github.com/zjzsu2000/CMPE297_AdvanceDL_Project/blob/main/pics/Errors.png)

### TensorBoard
* LSTM
-  Put5
![link](https://tensorboard.dev/experiment/IN9XplUvRbqhaVBvCPIJSg/)
-  Put10
![link](https://tensorboard.dev/experiment/oQljEuYVSvOLPDi17AtRww/#scalars)
Put21
![link](https://tensorboard.dev/experiment/h5KIjLjiQPmdk9cvD9JD6A/)
-  Call10
![link](https://tensorboard.dev/experiment/9tG0Hv68TmyaI7NBnbr2Ow/)
-  Call21
![link](https://tensorboard.dev/experiment/ZE4cErmZRXKKvUJRpHbjHQ/#scalars)

* Model2：			
Call 5		
https://tensorboard.dev/experiment/Bgx7f38NSgOtJQdNMXI9JA/#scalars
call10	
https://tensorboard.dev/experiment/y9MuyU77Tymi0Uz1Yb0NSA/#scalars
Call 21
https://tensorboard.dev/experiment/y9MuyU77Tymi0Uz1Yb0NSA/
					
put5		
https://tensorboard.dev/experiment/L208zOrlRziyfgiEm9RjjQ/#scalars
Put21
https://tensorboard.dev/experiment/L208zOrlRziyfgiEm9RjjQ/
	
* Model3:			
call5				
https://tensorboard.dev/experiment/X4dEGe3NQbOBOU5vFzHQuw/
Call21
https://tensorboard.dev/experiment/V2WF49BDQlK1spQ21eedfA/

Put5
https://tensorboard.dev/experiment/RY5C4BGKRIKpndYhO4sdqg/
Put21
https://tensorboard.dev/experiment/9zzUE8NcQoySec6DarEo9g/


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
