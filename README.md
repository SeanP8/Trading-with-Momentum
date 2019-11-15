# Trading-with-Momentum

## Objective

> Using a given dataset from Quotemedia, implement a trading strategy, and test to see if it has the potential to be profitable.\
Generated a trading signal based on a momentum indicator and computed the signal for the given time range and apply it to the dataset to produce projected returns.\
Performed a statistical test on the mean of the returns to conclude if there is alpha.

---

## Major Steps to achieve objective
    1. Resample close prices for each ticker
    2. Computed shifted Log Returns
    3. Computed the expected portfolio returns
    4. Ran a t-statistic on annualized rate of returns to find  
       corresponding p-value

---
## Conclusion
    I observed the p-value as 0.0733 p-value > alpha this would \
    indicate that there is some alpha in the strategy and would \
    ustify investigating further leading to backtesting strategy
    

