# NASDAQ-100-Stock-Analysis-and-Prediction

### Data Set Link: https://www.kaggle.com/datasets/kalilurrahman/nasdaq100-stock-price-data
- The Nasdaq Stock Market is an American stock exchange based in New York City. It is ranked second on the list of stock exchanges by market capitalization of shares traded, behind the New York Stock Exchange.
- Stock prices of all NASDAQ-100 index stocks (as on Sep 2021) from 2010

### Methodology:
- Build the Input dataset
- Run LSTM Model
- Generate Model Visualization
- Generate Summary

### Frameworks/Tools employed:
- Tensorflow/Keras
- Numpy/Pandas
- Matplotlib/Seaborn
- scikit-learn

### Models used for Prediction
- Facebook Prophet (which uses SKLEARN) and Neural Prophet (which uses PyTorch)
- prerequisite: idea of working of Prophet is recommended before using it :) [Link](https://facebook.github.io/prophet/)



This Notebook analysis and predicts of all NASDAQ 100 Stocks (eg : 'AMZN','TSLA','NVDA','GOOG','MSFT', etc)
### Microsoft Stock Prediction:
Let's predict stock price of Microsoft ('MSFT')

Graph Visualization of Opening Price of Microsoft:
![image](https://github.com/rushildpatel/NASDAQ-100-Stock-Analysis-and-Prediction/assets/73517149/754af3d0-5929-4e59-baa4-767e6bfc5ba8)


Graph Visualization of Closing Price of Microsoft:
![image](https://github.com/rushildpatel/NASDAQ-100-Stock-Analysis-and-Prediction/assets/73517149/c0d707cb-450e-4116-9095-237bf22ab29b)


Graph Visualization of Microsoft Model Forecast:
![image](https://github.com/rushildpatel/NASDAQ-100-Stock-Analysis-and-Prediction/assets/73517149/25ca260a-954f-45e4-bd2b-fb36eb94b68c)

- The Blue Line is the training data. Red line is the valid data and Yellow is the predicted data.
- More the Red and Yellow line are closer and overlapping lesser is the error and more accurate is the prediction.
- We calucate error using [RMSE](https://neptune.ai/blog/predicting-stock-prices-using-machine-learning#:~:text=RMSE%20gives%20the%20differences%20between,actual%20stock%20price%20is%2012%25.) as our metric. Test RMSE for MSFT = 11.506

Check out the predictions of all other stock with Visualizations in the jupyter notebook.


