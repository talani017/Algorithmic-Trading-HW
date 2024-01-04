# Algorithmic-Trading-HW
## Class Verification Report and Cumprod Actual vs Strategy returns of the baseline

![Alt text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/SVC%20Classreport.png)

![Alt text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Baseline%20Actual%20vs%20Strategy%20Graph.png)


## Class Verification Report and the Cumprod Actual vs Strategy graph for the case when the model is tuned by changinging the parameter of dataoffset from 3 months to 6 months


![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Tune6months%20Classreport.png)

![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Tune%20dataoffset6monthsActual%20vs%20Strategy%20cumprod.png)



## Class Verification Report and the Cumprod Actual vs Strategy graph  for the case when the model is tuned by changinging the parameter of Short window  from 4 to 50

![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Tune%20ShortEMA50%20Classreport.png)

![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Tune%20ShortEMA50%20Actual%20vs%20Strategy%20cumprod.png)


## Class Verification Report and the Cumprod Actual vs Strategy graph for the AdaBoost Model


![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Adaboost%20Classreport.png)

![Alt_text](https://github.com/talani017/Algorithmic-Trading-HW/blob/main/Adaboost%20Actual%20vs%20Strategy%20returns.png)


# Using the above graphs and evaluation reports we can see that even after tuning the baseline by canging the short window and the dateoffset it doesn't afftect the precison and accuracy of the model that much, there is a slight change in recall which causes a slightly noticable change in the f1 score. This is due to the fact that the f1 score is harmonic mean of Precison and Recall, and hence is more sensitive to slight changes in any one of them.
# Also from the graphs you can see that the strategy returns were close to or even better than the actual returns, except when the model was tuned by changing the short moving average window from 4 to 50. In this case the actual returns were way better than the Strategy Returns.

# For the AdaBoost model too the Strategy returns were close or better than the Actual Returns. THe Accuracy of this model was 0.55 which was similar to the above cases.The overall performance of this model was comparable to the Baseline.

