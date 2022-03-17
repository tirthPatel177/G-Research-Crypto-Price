# G-Research-Crypto-Price

## Submission Template
[LINK](https://www.kaggle.com/sohier/basic-submission-template)

## Iter API Intro
[Link](https://www.kaggle.com/sohier/detailed-api-introduction)

## Basic Linear Regression 
[Tutorial](https://www.kaggle.com/tirthpatel177/linear-regression-onthe-g-research-crypto/edit) *Note: This tutorial only uses a subset of data not the whole data set.*

- Author of this notebook were the competition host itself


## Model Evaluation or Comparison
Author's Explanation [Link](https://www.kaggle.com/c/g-research-crypto-forecasting/discussion/286778)

Notebook that shows how the target is Calculated [Link](https://www.kaggle.com/tirthpatel177/evaluating-a-model-in-crypto/edit)
[Author](https://www.kaggle.com/vi2018/g-research-crypto-repro-target-computation)


## Split the data
One of the easiest way to split the data is by *no. of entries*
```
train_data, test_data = entry_array[3:int(len(entry_array)*0.9)], entry_array[int(len(entry_array)*0.9):]
```


## Things to look at
[Everything you can do with time series (crypto)](https://www.kaggle.com/neomatrix369/everything-you-can-do-with-a-time-series-cryptos) - I think we should study this notebook in depth. This will be almost all we require for this project
