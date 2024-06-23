# AMD_MachineLearning_predictor

This project was build to predict when would be good days to buy or not buy AMD stock. Using historical data the model attempts to predict what days should AMD stock be bought. 1 = buy, 0= do not buy. 
For the data, I excluded all data from before 2021. The reason for this is that the economic conditions have changed drastically from 1980-2020. With the rise of AI and recovering economy, AMD growth factors and risks have changed dramatically.
A Random Forest was used to predict the stock price changes. Then I measured for the precision of the model. The precision of the model was 0.48. A backtest was then used to verify the accuracy of the model. 
With an accuracy of 0.48, I would not use this model to buy AMD stocks.
