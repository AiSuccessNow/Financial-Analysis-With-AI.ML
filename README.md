# **Financial Market Analysis With AI and Machine Learning**

###  **Projects By:** Augustine Ojo Bsc., MBA., Fintech (Harvard), Ai/ML (RiceU (Oct. 2024))
### **Project Goal:** To build a model to integrate the leading traditional trading and investing tools with the predictive prowess of Ai and Machine Learning enabled algorithms.
### **Data Attribution:** Financial Data was sourced from Yahoo Finance (yfinance)
## **................................**

## **Project Overview:**
The goal of this project was to build a model to integrate the old tools of trading and investing (technical, fundamental analysis etc.) with the powerful analytical and predictive prowess of the new and continuously improving Ai and Machine Learning enabled Algorithms. To achieve this, I applied my experience in trading and investing, combined with my education and knowledge of supervised, unsupervised and neural networks modeling techniques using Python programming language, 

The intended audience was the head of HR of an investment group, who just advertised an opportunity for a Quantitative Analyst to join their Portfolio Management team. The analysts role will include but not limited to: 
####
* Develop and enhance our existing stock selection models
* Research and develop new factors, strategies and stock selection models
* Provide routine support to Portfolio Managers for managing multiple portfolios
* Process large structured and/or unstructured datasets to extract predictive signals
* Present research and portfolio analysis results to key internal stakeholders
* Collaborate and effectively coordinate with cross-functional teams on a day-to-day basis
####
This project was designed to showcase my readiness for this job.

According to Scott Stern, VP Product Marketing & Strategy at OneStream software, a global leader in Ai financial forecasting, currently "only about **20% of finance team** are able to adopt Ai and machine learning in their everyday work." And as we say in real estate investing, _**Time is of essence!**_
*Reference: https://www.onestream.com/resources/video-sensible-ml/#resource*

Ai and Machine Learning is the latest disruptive technology to hit the global economy and everything else. This innovative technology presents a once in a lifetime opportunity to build the next Goldman Sachs, Blackrock or something better.

##  **Data Source**
The raw data for the project were scrapped from yahoo finance (yfinance). The data was then preprocessed, cleaned and feature_engineered before been saved as .csv file.  This was later imported and read with pandas into dataframes for anaylysis and modeling. Below are the references for the data.
* Stock Price: https://docs.google.com/spreadsheets/d/14FvqWm5S55jcb-NqOcXtgQwIFqwQ9kT_4d5kcrL0mDo/edit?usp=sharing
* Volume Data: https://docs.google.com/spreadsheets/d/17xYBfnE8A3zlUifj8s3CjwqYbw1szJaWNmlniytuRww/edit?usp=sharing

The daily adjusted closing prices and trading volumes data were used for the analysis, and to train and test the models.
###


The project was divided into two major parts: 
* **Part A:** Financial Market Evaluation With Technical Analysis
* **Part B:** Ai and Machine Learning for Financial Market
    * B1: Using Prophet Model to Predict Future Stock Prices 
    * B2: Financial Market application of Long Short Term Memory (LSTM) Neural Networks

## **Project Description:**

### **Part A: Technical Analysis and Charting**
The first part of this project was focused on the basics of technical analysis for exploration and analysis of a portfolio of stocks. In this part, I evaluated, analyzed and visualized the stock prices, stock volumes, returns and risks associated with the portfolio. Part one is designed to lay the foundation for a comprehensive overview of the market and provide a insights into  random behavior of unstructred finanacial market. The figures below were chosen to highlight how investros and traders have trying to tame the financial market monster, with the hope of earning decent returns on their efforts and capital invested. 

**See the figures below:** Note that figure descriptions are displayed _**below the figures**_ 
##
![image](https://github.com/user-attachments/assets/2a42ed28-96d5-42a2-bb91-2c48f9b54afd)
fig 1: Overview of Stocks Prices and Comparism:
* **Observations:** This chart reveals the incomprehensible, interwoven and noisy price actions of the financial market.

![image](https://github.com/user-attachments/assets/e3a72b15-6143-4f9a-a13d-676c4413381e)
Fig 2: Visualization of Normalized Stock Prices: 
* **Observation:** Stock price normalization _**cancels out market noise**_ and reveals the signficant outperformance of NVDA over other stocks, in this portfolio.
##

### **Volume Visualization:**
![image](https://github.com/user-attachments/assets/78dbf2c8-58e2-4c97-84c3-48cff83754dd)

Fig 3: Stocks Volume Visualization: 
* **Oberservations:**  Note the spike in volume (pink graph) or _**Accumulation**_ of NVDA stocks that started in 2017. This probably marks the beginning of institutional interest and accumulation of NVDA stocks  

![image](https://github.com/user-attachments/assets/739f8577-8620-44b8-a29c-d6a2a2f9a4b9)
fig 4: Normalized Stock Volume Visualization: 
* **Observations:** Normalizing the volume change the display of the dataset. The spike in volume (red graph) is probably due to the discovery of NVDA by the _**retail traders**_ and other slower investors like the banks etc.  

### **Visualization of Market Trend With Moving Averages**
![image](https://github.com/user-attachments/assets/8fe76c2b-9a95-40b6-9d27-31d90bb48763)
fig 5: Finding Market Trend with Moving Average Crossover: 
* **Observation:** This graph shows the _**Bullish Market Trend**_ whereby Close > SMA50 > SMA200 as shown in the plot.

### **Portfolio Daily Returns:**
![image](https://github.com/user-attachments/assets/97c8e6f7-d8db-4d5f-92cf-b56040f06d90)

fig 6: Stocks Daily Returns Ranges:
* **Observations:** Highly volatile stocks have a much wider price ranges than less volatile stocks. eg NVDA has a price range from -20 to +20 plus, giving it a possible price range of above $40 low to highest. majority of the stocks have about $-5 to $5 daily price fluctuations from high to low. This probably explains why its so very difficult for _**Day Traders**_ to make consistent profits in the long run.

![image](https://github.com/user-attachments/assets/e9fda4a0-a50d-4724-ad15-ab7ab82a1619)
Fig 7: Plotting The Cummulative Daily Returns 

###
![image](https://github.com/user-attachments/assets/82c8acb5-6ea4-4d9a-ace7-8cb1f0ca9b38)
fig 8: Heatmap Plot of Returns
* **Observation from HeatMap:** SPY and QQQ, the ETFs of S&P500 and Nasdaq respectively are very nicely correlated with each other and the large technology stocks like MIcrosoft (MSFT) and Apple stocks (AAPL). This is no surprise becasue the large technolgy stocks are parts of the ETFs.
#

### **Part B: Ai and Machine Learning and Financial Market Forecasting**
###
### **1, Modelling and Predicting Financial Market Prices with Prophet:**
The first section of the Ai Amchine learning was focused on the use of the Prophet Model to predict future prices and market trends.
The choice of Prophet Model was due to its ability to analyze and make predictions from datasets that exhibit seasonality trends and patterns; and the simplicity and interpretability (easy to understand) of the model output and predictions. Prophet was developed by Facebook and the predictions are based on single stock at a time.
(Expert Learning Assistant: https://bootcampspot.instructure.com/courses/6442/external_tools/313). See the figures below

* ### **Financial Market Price Predictions With Prophet Model:**
![image](https://github.com/user-attachments/assets/b49b8a5c-f1c2-421a-b5ce-5ac29e3550f9)
Fig 9: Visualization of Price Predictions of NVDA Based on PROPHET Model

![image](https://github.com/user-attachments/assets/0ec53bb5-4ac5-4809-be51-30849227151f)

Fig 10: Price Forecast for Nvidia (NVDA) From Prophet Model  

![image](https://github.com/user-attachments/assets/36fd11d1-653c-48a0-9b01-a647f2e3c3d4)

Fig 11: Forecast Components Visualization With Prophet Model
###

### **2: Financial Market Price Predictions With LSTM Neural Networks:**
This section is devoted to applying the Long Short Term Memory (LSTM) Neural network, a deep learning models complete with Keras and Tensorflow to predict the future prices and direction of stocks. LSTM networks are a type of Recurrent Neural Network (RNN) that are equipped to overcome the limitations common to traditional RNNs, particularly the short-term memory issues due to vanishing gradient problems. LSTM was chosen for the analysis because of its ability to remember and incorporate earlier sequences into formulating its predictions. See the figures below:


###
![image](https://github.com/user-attachments/assets/61e3a609-74b0-4f3f-ac0c-ff22348fd6db)

fig 15: LSTM Model Summary for NVDA Stock Price Predictions

![image](https://github.com/user-attachments/assets/c1d22d35-d7a3-4691-81ce-3f6243cf4891)

Fig 16: Model History Display Table

![image](https://github.com/user-attachments/assets/e0f97eeb-c208-4a4a-8618-9585d6847827)

Fig 17a: Original Stock Prices vs LSTM Predicted Prices

![image](https://github.com/user-attachments/assets/fcf9b53f-a8bf-45df-a598-3e7adf50719f)

Fig 17b: Original Stock Prices vs LSTM Predicted Prices **Last 300 Periods**

![image](https://github.com/user-attachments/assets/48c455cb-a03f-4ca9-97d1-fe4d70d4c9eb)
![image](https://github.com/user-attachments/assets/ffa311c3-16d1-441c-9a5e-f0ef9ddde86c)
![image](https://github.com/user-attachments/assets/02ec0061-edd6-4966-a746-60bc9624b581)


Fig 18: Predictions vs Closing prices vs Their Percentage Differences (Normalized)
##

## **Areas For Further Research and Investigate:** 
* **Data:** Sourcing higher quality realtime data to lifetest/forward test models
* **Kaizen:** ongoing testing and optimization of models to improved performance and accuracy. eg. Parameter tuning etc.
* **Partnership:** Probably seeking a partner or investor to fund further research and monetization of models 

## **Future Product Developments and Possibilities:**
* **Automation:** Automated/Semi_Automated trading and investing with Ai and Machine Learning
* **Monetization:**  Provide financial forecasting / Robo_advisory services through partnership with an incumbent
* **Fundamental Analysis:**  Ai and Machine learning with deep learning to unlock and automate bankable insights from fundamental data. 
* **Sentiment Analysis:** Financial Market Sentiments Analysis with Natural Language Process and Neural Networks, given high quality realtime data. 
 
## **Conclusions and Inferences:**
* The financial market is an incredibly irrational beast with incomprehensible, interwoven and noisy random walk of price actions.
* Normalization streamlines both price and volume data and cancels out market noise, to reveal stocks with signficant outperformance potential e.g. NVDA.
* A careful study of volumes can reveal intituttional investors interest and accumulation in stocks
* Prophet Model is good for time series predictions and it has been exceptionally effective in predicitng Nvidia prices. Haven said that, Prophet can be unreliable and its been deprecated by Meta (Facebook) which means it may not supported in the future.
* LSTM Networks has a brighter future with better stock prices predictions accuaracy, compared to Prophet Model. However, it requires a large volume of data over a very long period to train in improve future predictions.
* Its is still unknown how well the models will perform in forward testing with realtime data.
* Granted that this project was limited by many factors, especially data and time, its save to say that more work is needed to vet the models for long term profitable performance in the financial market place.

## **References:**
Scott Stern andScot Leshinski, Product Expert Video Series, Sensible ML. https://www.onestream.com/resources/video-sensible-ml/#resource
