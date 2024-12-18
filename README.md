# **GRU Model for Financial Predictions**

This repository contains the initial implementation of a GRU (Gated Recurrent Unit) model designed for financial predictions across multiple asset classes. This model aims to provide accurate forecasts for various financial instruments, including indices, cryptocurrencies, commodities, and currency pairs. Below, you will find detailed performance metrics for each asset class and links to external resources that complement this project.

## **Performance Metrics**

### 

### **BTC-USD (Bitcoin)**

| Metric | Open | High | Low | Close |
| ----- | ----- | ----- | ----- | ----- |
| Mean Squared Error | 0.0006704011 | 0.0007466893 | 0.0010460546 | 0.0010510000 |
| Mean Absolute Error | 0.0189357042 | 0.0207899107 | 0.0244501190 | 0.0251394672 |
| R-squared | 0.9698693476 | 0.9671408209 | 0.9520648807 | 0.9536147883 |
| Median Absolute Error | 0.0147797754 | 0.0157247866 | 0.0198321750 | 0.0206766406 |
| Explained Variance Score | 0.9714662622 | 0.9682738453 | 0.9575608982 | 0.9563927096 |


### **![][image1]**

### **GC=F (Gold Futures)**

| Metric | Open | High | Low | Close |
| ----- | ----- | ----- | ----- | ----- |
| Mean Squared Error | 0.0006704011 | 0.0007466893 | 0.0010460546 | 0.0010510000 |
| Mean Absolute Error | 0.0189357042 | 0.0207899107 | 0.0244501190 | 0.0251394672 |
| R-squared | 0.9698693476 | 0.9671408209 | 0.9520648807 | 0.9536147883 |
| Median Absolute Error | 0.0147797754 | 0.0157247866 | 0.0198321750 | 0.0206766406 |
| Explained Variance Score | 0.9714662622 | 0.9682738453 | 0.9575608982 | 0.9563927096 |


### **![][image2]**

### **EURUSD (Euro/US Dollar)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.0003879169 | 0.0004876292 | 0.0005445911 | 0.0003651724 |
| Mean Absolute Error | 0.0158024339 | 0.0179194147 | 0.0182679915 | 0.0155702525 |
| R-squared | 0.9101155429 | 0.8892027422 | 0.8765603505 | 0.9154974316 |
| Median Absolute Error | 0.0132580484 | 0.0159090454 | 0.0155098954 | 0.0136890470 |
| Explained Variance Score | 0.9107513364 | 0.8902119109 | 0.8874938781 | 0.9170630250 |


### 

### **![][image3]**

### **GSPC (S\&P 500 Index)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.0006503769 | 0.0006529812 | 0.0006666432 | 0.0009187557 |
| Mean Absolute Error | 0.0187974513 | 0.0194058691 | 0.0198970860 | 0.0233750671 |
| R-squared | 0.9516866515 | 0.9538492619 | 0.9504676043 | 0.9351719127 |
| Median Absolute Error | 0.0138990470 | 0.0166170954 | 0.0170245137 | 0.0193339874 |
| Explained Variance Score | 0.9526338713 | 0.9568179300 | 0.9515982439 | 0.9413512079 |


### **![][image4]**

## **Related Websites**

### [**Predict Price**](https://predict-price.com/)

Free AI-powered short-term (5/10/30 days) and long-term (6 months/1/2 years) forecasts for cryptocurrencies, stocks, ETFs, currencies, indices, and mutual funds.

### [**Magical Prediction**](https://magicalprediction.com/)

Get free trading signals generated by advanced AI models. Enhance your trading strategy with accurate, real-time market predictions powered by AI.

### [**Magical Analysis**](https://magicalanalysis.com/)

Discover free trading signals powered by expert technical analysis. Boost your forex, stock, and crypto trading strategy with real-time market insights.

## **About This Project**

This GRU model is an initial implementation, released for public use. The project demonstrates the potential of deep learning models for financial predictions. While this repository focuses on GRU, I have also utilized other models, the code for which is available on my GitHub[https://github.com/taleblou/].

## **How to Use**

1. Clone this repository.  
2. Install the required libraries: `pip install -r requirements.txt`  
3. Prepare your dataset and follow the instructions in the notebook or script.  
4. Run the model and evaluate its performance using the provided metrics.

## **License**

This project is open-source and available for public use under the MIT License. Contributions and feedback are welcome\!

[image1]: <https://raw.githubusercontent.com/taleblou/GRU-Price-Prediction/refs/heads/main/Plot/GRU_BTC-USD.png>
[image2]: <https://raw.githubusercontent.com/taleblou/GRU-Price-Prediction/refs/heads/main/Plot/GRU_GC%3DF.png>
[image3]: <https://raw.githubusercontent.com/taleblou/GRU-Price-Prediction/refs/heads/main/Plot/GRU_EURUSD%3DX.png>
[image4]: <https://raw.githubusercontent.com/taleblou/GRU-Price-Prediction/refs/heads/main/Plot/GRU_%5EGSPC.png>
