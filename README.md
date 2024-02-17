# Stock Trend prediction using Deep Learning
(This project was done as a part of my coursework for "CS543: Massive Data Storage, Retrieval and Deep Learning" in Fall 2023 under Prof. James Abello at Rutgers University)
## Introduction: 
In the complex world of stock market dynamics, where influences range from economic conditions to social media sentiments, making informed investment decisions is paramount. This project leverages advanced deep learning models, specifically CNN+LSTM and AR-LSTM, to forecast stock price movements. The dataset, sourced from Yahoo Finance, spans Netflix stock data from January 2020 to December 2023. Recognizing the impact of social media, Twitter data is incorporated for sentiment analysis, adding a nuanced layer to stock predictions.

## Data Collection and Preprocessing: 
Utilizing the 'yfinance' Python library for stock data and Twitter API for sentiment data. Preprocessing involves handling missing values, date conversion, and normalizing stock prices.

<img width="800" alt="Picture 1" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/825c75fc-babd-4820-94bc-ec127d2befbe">

<img width="800" alt="2" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/fbbcbb26-f409-495c-a2bb-250ea9f31958">
## Modeling Approaches: 
Employing CNN+LSTM and AR-LSTM models for stock price prediction. The former focuses on feature extraction, while the latter integrates autoregressive and LSTM components for a comprehensive approach.
## Sentiment Analysis Integration: 
Incorporating sentiment polarity from Twitter data into the stock dataset, recognizing the impact of social media on market dynamics.
### Comparative Analysis: 
Evaluating the performance of CNN+LSTM and AR-LSTM using mean square error as the loss function, showcasing the efficacy of each model in predicting stock movements.
### Real-time Evaluation: 
Assessing the robustness of models against real-time data, validating their predictive capabilities beyond historical trends.
Results:
### Stock Price Prediction: 
Both CNN+LSTM and AR-LSTM predict Netflix stock movements until January 01, 2024. AR-LSTM demonstrates higher accuracy, especially in closing price values.
### Testing Accuracy: 
Mean Squared Error values indicate improved accuracy when Twitter sentiment data is considered during training.
## Conclusion:
The project successfully integrates deep learning models with social media sentiments for stock prediction. While CNN+LSTM captures overall trends, AR-LSTM outperforms, emphasizing its proficiency in predicting both trends and closing values. The inclusion of Twitter sentiment data significantly improves model accuracy, as reflected in reduced Mean Squared Error values.
## Future Work:
The project lays the foundation for future research by highlighting the impact of social media on stock predictions. Further exploration could involve refining models, incorporating additional external factors, and expanding to different stocks and time periods.
