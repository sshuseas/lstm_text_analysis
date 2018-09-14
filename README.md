# PREDICTING A GOOD OR BAD DECISION, and why both are valuable


## Abstract:
Application of Long-Short-Term-Memory RNN on text data to predict behavior and performance.
Conventional methods attempt to use a LSTM NN to predict stock prices using historical stock data.
The baseline model was built using Keras with a TF backend, and public data was pulled from yahoo finance.
This model predicted stock price trend, but drastic changes in stock price took several days for model to 
adjust, leading to a net loss of approximately 30%. Using private text data from a particular hedge fund,
a new model was built using Keras, scikit learn, xgboost, and a myriad of other analytical libraries. This
model used semantic analysis to capture key behaviors and characteristics a portfolio manager exhibits days 
before a major trade. Through this, these characteristics could predict whether a certain position was 
good or bad. These positions were chosen by a determined probability threshold, thus the model could only 
identify which positions were the real money makers, or losers. In conclusion, the behavioral algorithm 
performed better than the aggregate returns of the hedge fund's top 5 performing portfolio managers.

## Note On Data:
This particular dataset with which the behavioral model was built, is highly confidential. In order to obtain the data, I was required to sign an NDA, and am thus unable to include any specifics of the data, code, or functions used to model my predictions. I am available on linkedin @ https://www.linkedin.com/in/sageh/ if you would like to ask any additional questions regarding my project.

The performance of the behavioral model is shown in the cumulative_returns image, which shows how the algorithm performed compared to the fund's top 5 performing PMs and fund average.