# Algorithmic Trading Strategy Project
## Introduction
This project aims to build a trading algorithm that maximizes returns using simple moving averages (SMA) as input features. The project involves three steps:

1. Tune the training algorithm by adjusting the size of the training dataset.
2. Tune the trading algorithm by adjusting the SMA input features.
3. Choose the set of parameters that best improved the trading algorithm returns.
## Step 1
The size of the training dataset is adjusted by slicing the data into different periods. The results show that adjusting the size of the training dataset from 3 months to 24 months did not produce any actual returns until April 3, 2020.

## Step 2
The SMA input features are adjusted by changing one or both of the windows for the algorithm. The results show that increasing both the short and long windows of the algorithm led to better results, where the actual returns outperformed the strategy returns from August 28, 2017, through January 20, 2021.

## Step 3
The set of parameters that best improved the trading algorithm returns is chosen. The best set of parameters is the one where both the short and long windows are increased. A PNG image of the cumulative product of the actual returns vs. the strategy returns is saved, and it shows that the actual returns outperformed the strategy returns throughout the entire period.

## Conclusion
This project shows that adjusting the SMA input features by increasing both the short and long windows produces the best results for the trading algorithm. The project also highlights the importance of tuning the training algorithm by adjusting the size of the training dataset.





