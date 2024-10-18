# Financial-Analysis-and-Predictions-With-AI.ML

## **Project Overview:**

The goal of the project is to demonstrate the predictive powers of Ai and Machine Learning and its use case in financial market analysis and price predictions. Daily adjusted closing prices and volume of stocks in the portfolio were used for the analysis, and to train the models.

The datasets were obtained through yahoo finance (yfinance), and preprocessed and cleaned before been saved as a .csv which was later imported for the modeling.

The stock market was selected for this project because of my personal interest and experience in trading the market with technical analysis. Applying Ai and Machine Learning to stock trading is futuristic and seems like the next BIG thing to stock trading and investment, and I want to be a part of this revolution. 

Also, the complex and dynamic nature of price actions of financial products make them a perfect fit for Ai and Machine Learning.

The project was divided into three parts, starting with the known and familiar basic technical analysis and charting, through a gradual progression to the Prophet Model and finally to the deep world of Ai and Machine Learning.


## **Project Description:**

**Part One:** The first part of this project was focused on the basics of technical analysis for exploration and analysis of a portfolio of stocks. In this part, I evaluated, analyzed and visualized the stock prices, stock volumes, returns and risks associated with the portfolio. Part one is designed to lay the foundation for a comprehensive overview of the market and provide a insights into  random behavior of unstructred finanacial market. The figures below were chosen to highlight how investros and traders have trying to tame the financial market monster, with the hope of earning decent returns on their efforts and capital invested. 

**See the following figures:** Please Note that figure descriptions are displayed _**below the images**_ 
* fig 1; Overview of Stocks Prices Comparism 
* fig 2: Visualization of Normalized Stock Prices
* fig 3: Stocks Volume Visualization
* fig 4: Normalized Stock Volume Visualization
* fig 5: Stocks Daily Returns Ranges
* fig 6: Heatmap Visualization of returns
* fig 7: Market Trend With Moving Average Crossover
* Fig 8: Visualization of Cummulative Daily Returns
##

**Part Two:** The second part of the project was focused on the use of the **Prophet Model** to predict future prices and trends for the market. The choice of Prophet Model was due to its useful for analyzing and making predictions from datasets that exhibit seasonality trends and patterns; and the interpretability of the model output and predictions. Prophet  was developed by Facebook.
(Expert Learning Assistant: https://bootcampspot.instructure.com/courses/6442/external_tools/313)
##


**Part Three** was devoted to studying the Long Short Term Memory (LSTM) Neural network, deep learning models complete with Keras and Tensorflow to predict the future prices and direction of the specific stocks. LSTM networks are a type of Recurrent Neural Network (RNN) that are equipped to overcome the limitations common to traditional RNNs, particularly the short-term memory issues due to vanishing gradient problems. LSTM was chosen for the analysis because of its ability to remember and incorporate earlier time steps in the sequence into formulating its predictions.

### **Stock Prices Visualization:**

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
##

### **Visualization of Market Trend With Moving Averages Crossovers:**
![image](https://github.com/user-attachments/assets/8fe76c2b-9a95-40b6-9d27-31d90bb48763)
fig 8: Moving Average Crossover: 
* **Observation:** This graph shows the _**Bullish Market Trend**_ whereby Close > SMA50 > SMA200 as shown in the plot.

##
### **Portfolio Daily Returns:**
![image](https://github.com/user-attachments/assets/97c8e6f7-d8db-4d5f-92cf-b56040f06d90)

fig 5: Stocks Daily Returns Ranges:
* **Observations:** Highly volatile stocks have a much wider price ranges than less volatile stocks. eg NVDA has a price range from -20 to +20 plus, giving it a possible price range of above $40 low to highest. majority of the stocks have about $-5 to $5 daily price fluctuations from high to low. This probably explains why its so very difficult for _**Day Traders**_ to make consistent profits in the long run.

![image](https://github.com/user-attachments/assets/e9fda4a0-a50d-4724-ad15-ab7ab82a1619)
Fig 6: Plot of Cummulative Daily Returns 

![image](https://github.com/user-attachments/assets/82c8acb5-6ea4-4d9a-ace7-8cb1f0ca9b38)
fig 7: Heatmap Plot of Returns
* **Observation from HeatMap:** SPY and QQQ, the ETFs of S&P500 and Nasdaq respectively are very nicely correlated with each other and the large technology stocks like MIcrosoft (MSFT) and Apple stocks (AAPL). This is no surprise becasue the large technolgy stocks are parts of the ETFs.
##




##

# **AI AND MACHINE LEARNING IN FINANCIAL MARKET** 

### **Financial Market Price Predictions With Prophet Model:**
![image](https://github.com/user-attachments/assets/b49b8a5c-f1c2-421a-b5ce-5ac29e3550f9)
Fig 12: Visualization of Price Predictions of NVDA Based on PROPHET Model

![image](https://github.com/user-attachments/assets/0ec53bb5-4ac5-4809-be51-30849227151f)

Fig 13: PRice Forecast for NVDA From Prophet Model  

![image](https://github.com/user-attachments/assets/36fd11d1-653c-48a0-9b01-a647f2e3c3d4)

Fig 14: Forecast Components plots With Prohpet

**Financial Market Price Predictions With LSTM Neural Networks:**

![image](https://github.com/user-attachments/assets/61e3a609-74b0-4f3f-ac0c-ff22348fd6db)

fig 15: LSTM Model Summary for NVDA Stock Price Predictions

![image](https://github.com/user-attachments/assets/c1d22d35-d7a3-4691-81ce-3f6243cf4891)

Fig 16: Model History Display Table

![image](https://github.com/user-attachments/assets/e0f97eeb-c208-4a4a-8618-9585d6847827)

Fig 17: Plot of Original Stock Prices vs LSTM Neural Network Predicted Prices

![image](https://github.com/user-attachments/assets/8907dec2-7e06-4a6a-86a4-c20bf60adb5c)

Fig 18: Table of Normalized Predictions vs Closing prices vs the differences expressed in Percentages

