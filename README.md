# **Crypto Returns Forecasting**
## **Team Pied Pipers**
CSE523 - Machine Learning Course, Ahmedabad University
## Introduction
Crypto currencies have been a major trading market with over 40 billion$ worth of crypto-currencies being traded every day. However, one of the major issues is with its volatility. Here, we have attempted to mitigate the volatility by answering a question that is it possible to forecast short-term returns for various types of crypto-currency with an acceptable accuracy using classic machine learning algorithms. We used 2 different Machine Learning approaches to achieve this: Statistical method called ARIMA and Ensemble learning method called LGBM. Dataset is taken from an ongoing competition on Kaggle. Dataset contains crypto-trading data from 2018-2021 for 14 different crypto-currencies. We performed EDA on dataset, applied several versions of Regression which first lead us to ARIMA and subsequently to LGBM, and tuned hyper parameters to achieve the best possible results.
## Results
For different algorithms, results are shown below in a graphical format. For detailed reading and analysis, please refer to the report [here](https://github.com/tirthPatel177/G-Research-Crypto-Price/blob/main/report/5_Pied_Pipers_Mid_Sem_Project_Report.pdf).

### EDA

#### Closing Price vs Time Period of Bitcoin and Ethereum

<img src = "https://user-images.githubusercontent.com/73438608/193521652-7b746a1e-2973-4610-a139-268387ef1cc6.png" width = "500px"/>
<img src = "https://user-images.githubusercontent.com/73438608/193521428-fc2737cc-e334-43e1-a86b-55083ca42951.png" width = "500px"/>

<br>
</br>

#### Target vs Time Period of Bitcoin and Ethereum

<img src = "https://user-images.githubusercontent.com/73438608/193522090-10c49fd6-ad2a-4654-891a-c1fa89560244.png" width = "500px"/>
<img src = "https://user-images.githubusercontent.com/73438608/193522209-bebbf939-e138-4f4c-933e-cb560cf07a50.png" width = "500px"/>

<br>
</br>

#### Correlation Matrix
<img src = "https://user-images.githubusercontent.com/73438608/193523525-7dea6fac-773a-484a-816e-84bfb37c2c01.png" width = "500px"/>


### Linear Regression
#### Target vs Time Period plot for Binance
<img src = "https://user-images.githubusercontent.com/73438608/193527566-6db46038-0800-469a-b643-329a1775bee5.png" width = "500px"/>

### ARIMA
#### Target vs Time Period plot for Binance
<img src = "https://user-images.githubusercontent.com/73438608/193528895-bac353ac-2e1a-4e1d-8bbc-a30df0a0510d.png" width = "500px"/>


