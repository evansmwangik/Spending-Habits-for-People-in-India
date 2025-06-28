# Spending Patterns for People in India
## Overview
In this project, I analyze the spending patterns for people in India.

I go through their overall spending patterns then go down to the different subgroups provided in the data such as analysing their transactions by age, transaction types, hours of day etc.

I start first by trying to clean any data misalignments, which I found none, then progressively dissect through the data to the different categories. You can find my analysis ([here](https://github.com/evansmwangik/Spending-Habits-for-People-in-India/blob/master/UPI%20Transactions%202024%20Dataset%20EDA1.ipynb))

## Purpose
1. **Data Exploration.** Data Cleaning & Data Visualization
2. **See what insights we can garner from the exploration.** Any insights gathered will be of use to anyone interested in learning about the people living in India.

## Conclusion
Having done an analysis on this data, I come to the following conclusions:
1. The frequency with which the Indian people transact follows a certain trend throughout the hours. decreasing(0000hrs-0400hrs) to reach it's lowest, increasing(0500hrs-1200hrs) to reach it's second highest value within the day, decreasing(1300hrs-1400hrs) to reach it's second higher low, increasing(1500hrs-1900hrs) to reach it's highest for the day, then finally decreasing from there to 2300 hrs.
- This has been supported by various factors such as; having almost level average amounts spending throughout the day which gives us the quality of our trend analysis, the median values for every hour are within the same range further confirming and giving ue the counlution of this finding.
- The outliers found in the dataset are distributed almost evenly across the hours, hence why we had closely matching averages with the difference between the lowest average point and the highest average point not exceeding 150 INR.

2. The leading 3 merchant categories where transactions were directed to were `shopping`, `grocery` and `utilities` and the trailing 3 were `shopping`, `grocery` and `utilities`. This remains consistent through the hourly datasetexcept for one instance, 1am, where the `fuel` category beats the `utilities` category.

3. The difference between the transactions happening during the weekdays and the weekends only hugely differ by sum of the amounts transacted and not by differing weights on categories spent on. The order in which the different categories are distributed within the weekdays is the same as the weekends, no change. The averages of the amounts spent, which would show the different categories valued in the weekdays and the weekend and their difference, are closely within the same ranges. Showing that their behavior on spending remains intact throughout the week(s).

4. The most used transaction type is P2P with 45% usage followed by the others in this order, P2M (35%), Bill Payment(15%), Recharge(5%). These %age closely match with the %age total amounts transacted through. Generally, the payment options are distributed to everyone in those %ages and no certain groups, by status, are limited to certain payment types.

5. Finally the age group that transacts the most is 26-35(35%) years. Ages 18-25(24.9%) and 36-45 almost have a tie but ages 36-45(25.1%) have the lead by a small margin,which are then followed ages 45-55(9.9%) and 56+(5%) respectively.
- The amounts plots, show us that 26-35(35.4%) years transact the most amounts of money followed by ages 36-45(27.3%) (with a noticeable difference from the amounts transacted by ages 18-25), then ages 18-25(22.7%), then 45-55(10.1%) and finally 56+(4.5%).

6. DO different age groups prefer different transaction types that others? Well, according to the data, the different transaction types follow the findings in point 4 across all age groups.


This dataset was gotten from ([Kaggle](https://www.kaggle.com/datasets/skullagos5246/upi-transactions-2024-dataset?resource=download)).




