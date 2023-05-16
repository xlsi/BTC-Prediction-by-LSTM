# BTC Prediction by LSTM
The project mainly try to use LSTM and static database to predict BTC prices. 
* Time Window: 10 days
* predict horizon: 1 day average price
* Features in total: 61
* Dated Between：2020/9/16 ~ 2021/9/17

The main directory and files of this code are as follows:  
--------- *cleaned data_new.csv* (Raw cleaned data)  
--------- *all_data_new.csv* (Raw integrated data)  
--------- *bitcoin_final.ipynb* (Code)  
--------- *Bitcoin price prediction.pdf* (Report)  


## **1 Data Input**
### **1.1 Bitcoin property and network**
Bitcoin Daily Average Prices, Hash Rate, Miner Rewards, Miner Reserves,…

### **1.2 Bitcoin Marketing and trading**
Number of Large Transactions, Average Transaction Size, Average Balance, Average Time Between Transactions, …

### **1.3 Global economic indicators**
Gold price, US dollar index, Dow Jones Commodity index, … 

### **1.4 Investors and Media Attention**
Google trend, Twitter positive, Twitter negative, …

### **1.5 Prices of Other Cryptocurrencies and BTC Index**
 Ethereum, Dogecoin, CCI30*

 <img src="https://github.com/xlsi/BTC-Prediction-by-LSTM/blob/main/picture/data_input.PNG" width="400" height="300">


## **2 Model**
 <img src="https://github.com/xlsi/BTC-Prediction-by-LSTM/blob/main/picture/lstm.PNG" width="400" height="300">


## **3 Model Improvement**
 Steps | RMSE
 ---- | -----  
 Original Attempt  | 0.04543
 Adding Features  | 0.03101
 Feature Selection  | 0.0264
 Smoothing  | 0.0264
 Final RMSE  | **0.02631**
 <img src="https://github.com/xlsi/BTC-Prediction-by-LSTM/blob/main/picture/model_performance.PNG" width="400" height="300">

***
Specially thanks for Prof. Pang and other indutry partners of MSBA for their guidence and review.

Our project is chosen to be **One Of Outstanding Projects** that are qualified to present in front of reviewers from industry partners of NUS MSBA and the whole class. 
