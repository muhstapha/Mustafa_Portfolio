# Stock Market Prediction Using LSTM Neural Networks to Predict Volatile Time Frames
Long Short Term Memory (LSTM) are a subset of neural networks used to recognise patterns in data and are extremely valuable for stock market forecasting. With recent economic events, the stock market has experienced extremely volatile price movements. This project uses the recent volatile stock market data to predict volatile time frames for The Boeing Company (BA) and Zoom Video Communications, Inc. (ZM). A LSTM model was built and assessed by predicting two specific time periods of volatility caused by economic events for the mentioned stocks.

*My Final MSc Project can be found in my profile under the name: 
  * Mustafa_Alkatib_ProjectMSc_180452927

*The LSTM model built using Python is named as the file:
  *ProjectMSc_LSTM_model.py

## The Boeing Company (BA) ##
* BA experienced a huge crash in March 2020 due to the Covid-19 pandemic. 
* BA and Airbus have a duopoly in the aircraft industry. It almost seemed certain that once travel restrictions had come into effect during the pandemic, the public would panic and sell off BA shares. BA had started to see a sharp fall in its price in February 2020 just before the pandemic was announced. BA saw a 70% fall in its price from February 2020 to the historical stock market crash on March 16th, 2020. However, over the past few years, since 2017, the company has been trading fairly volatile. I used BA’s stock price from 2017 to predict this huge stock market crash. I expect the model to underperform since it is running on nothing but the ‘Close’ price data to make predictions. The LSTM model wouldn’t know of a pandemic with its univariate design, andtheoretically the model should underperform when predicting
BA’s stock.
* Using data from November 2017 I used my LSTM model to predict this crash:
![image](https://user-images.githubusercontent.com/72275728/187898752-5c6a55a0-6472-40ad-b140-27e118cac823.png)
## Zoom Video Communications, Inc. (ZM) ##
* Before the pandemic, ZM had very slow market activity after initially trading publicly in April 2019. Trading at $107.47 just before the World Health Organization (WHO) declared COVID-19 a pandemicin March 2020, there was a huge spike in the share price. ZM saw a 425% rise in its stock price reaching an all-time high of $559 in October 2020.
* However, during the period where the Pfizer-BioNTech COVID-19 Vaccine was announced in November 2020, ZM saw a 20% drop in its stock price. During this period of volatility, I felt that using ZM was an applicable stock to test how my model would perform.
* Using data from March 2020 to predict the activity in the market in December 2020:
![Screenshot 2022-09-01 115922](https://user-images.githubusercontent.com/72275728/187898612-309cf016-5dc4-4203-adb0-56d85d759c90.png)
