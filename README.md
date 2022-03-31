**Problem Definition**

Your client is a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful. Given the following information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set:  

Historical data of demand for a product-center combination (Weeks: 1 to 145)
Product(Meal) features such as category, sub-category, current price and discount
Information for fulfillment center like center area, city information etc.
 
** Data Dictionary**
 
1. Weekly Demand data (train.csv): Contains the historical demand data for all centers, test.csv contains all the following features except the target variable


 ![image](https://user-images.githubusercontent.com/96159329/160981050-9db009a1-da52-4cc0-8639-f347d290b7a3.png)

![image](https://user-images.githubusercontent.com/96159329/160981097-adb87718-481e-4397-a0e5-ef5d95d7defa.png)

![image](https://user-images.githubusercontent.com/96159329/160981148-0ef4ab45-fe8d-49f5-9061-717c43193873.png)

**Evaluation Metric**
The evaluation metric for this competition is 100*RMSLE where RMSLE is Root of Mean Squared Logarithmic Error across all entries in the test set.

Public and Private Split
Test data is further randomly divided into Public (30%) and Private (70%) data.

Your initial responses will be checked and scored on the Public data.
The final rankings would be based on your private score which will be published once the competition is over.
