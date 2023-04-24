# Stock-Price-Predictor
Stock Price Predictor for ML Challenge, HackRush 2023 IIT Gandhinagar
## 3. ML Challenge [C]
Stakeholders: Dwip Dalal

Forecasting Stocks using AI
100 points

In an hypothetical world you are an experienced stock market dealer, your goal is to leverage AI and algorithms to earn profits. During your research, you came across the internal workings datasheet of a company named TGD, which comprises three subsidiaries: TGD Consultancy, TGD Automobiles, and TGD Power. You feel that the stock prices of these companies are dependent on this dataset, and there is also some interdependence between the stock prices of these three subsidiaries.

To make informed decisions, you aim to study and analyze the dataset to forecast the values of TGD Consultancy, TGD Automobiles, and TGD Power share down the line. This will enable you to make timely buy and sell decisions, maximizing your profits.

Side note:
In this hypothetical world stock price are collected on daily basis. And their timeline is different from ours.

Join here: Kaggle Link

—--------------------------Bonus—------------------------------
Uncertainty 
30 points

The stock market is a highly volatile and unpredictable environment, and making accurate predictions with 100% certainty is not possible. Therefore, to ensure the reliability of your predictions, it is important to generate an uncertainty score along with the predicted values. This score will help you assess the level of confidence in your predictions and enable you to make more informed investment decisions.

Visualization
20 points

In addition to the above requirements, it is important to note that extra points will be awarded to participants who create exemplary visualizations that provide deeper insights into the workings of their models (eg. distribution of attention across the input features, the working of the model at each stage of the training process, etc)

The ability to effectively communicate the findings and insights obtained through data analysis and machine learning models is a critical aspect of stock market trading. Therefore, participants who can present their results using visually appealing and informative charts, graphs, and diagrams will get bonus points. (Note here we expect advanced techniques like LIME, etc). The visualization should provide a comprehensive understanding of the underlying data and the modeling process, enabling the audience to appreciate the quality of the model and the reliability of its predictions. 

Deliverable:
Final score shall be calculated based on the Leaderboard and Jupyter notebook (or .py files) submission.


Prediction score =  Sum of the value of all 3 stocks. (i.e. TGD Automobiles Share price + TGD Consultancy Share price + TGD Power Share price)

The score is calculated based on predictions. Metric: RMSE score 

Final score = Leaderboard score + Uncertainty score + Visualization Score

The Jupyter notebook should contain code for your final model that you submitted on the leader board (Note: It should be reproducible). It can also contain bonus task scores and visualizations. Uncertainty evaluations should be for you final model submitted.

Note: As this is a hackathon, you are encouraged to make use of any resources that are freely available, including open-source codes, pre-trained models, and other features. Don't hesitate to take advantage of these resources, and feel free to use them without changing variables or comments. (cite them in jupyter notebook)

Link for resource: 

Libraries information: https://github.com/dwipddalal/Resources_of_ml/blob/main/ML%20Material.pdf
Huggingface: https://huggingface.co/docs/transformers/model_doc/time_series_transformer
You can use any OpenSource features like this: https://github.com/AIStream-Peelout/flow-forecast
For any other resource required refer: https://github.com/dwipddalal/Resources_of_ml

(Hints) Keywords: Multi-task, Multi-variate time-series forecasting, Transformers, Uncertainty prediction (Dropout, Bayesian Inference, etc)

Judging Criteria:
Position 1 on leaderboard = 100 points
Position 2 on leaderboard = 90 points
Position 3 on leaderboard = 80 points
And so on.

Uncertainty estimation if correctly done for their model then full 30 points (Binary Grading). Note uncertainty needs to be calculated for each of the three share prices individually. (And not on their combined sum) 
