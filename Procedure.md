# US Steel Kosice hiring tasks

### Procedure of the Bitcoin rate prediction

1. Import required packages
2. Create dates variables that will be used to fetch current and historical data from coindesk api
3. Create list of dates that will be used for prediction and visualization (note: used 30 day period)
4. Fetch current rate in USD using coindes api
5. Fetch historical rates in USD using coindesk api
6. Create Data Frame with all the rates using dates as indexes
7. Plot the current rate flow
8. Create a linear regression model (note: I used 30-day period for prediction which might be not ideal - opportunity for improvement of both period and model itself)
9. Prediction of the flow rate (note: I used model to predict flow rate in USD for the next 5 days)
10. Create Data Frame with the predicted rate flows
11. Plot the current rate flow along with the predicted values
