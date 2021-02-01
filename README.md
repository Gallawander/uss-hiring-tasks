# US Steel Kosice hiring tasks

## Task 1 - Bitcoin price predictor API

The main goal of this task is to create API with predictions of bitcoin price. There are only few requirements.

### Main task

Predictions must be based on all available data so when I call price prediction API on 15:30 prediction should use all relevant data available even the newest one. Live updates of bitcoin prices should be drawn from some free public API (f.e. https://www.coindesk.com/coindesk-api).

#### Bonus task
Create simple web UI to plot bitcoin prices used by prediction with the prediction itself.

### Some notes

Task is defined vaguely on purpose. It is on you to decide which libraries you want to use, how will API response look like, how will API endpoint look like and so on. You can use any public resource of data or any publicly available API for bitcoin prices. You can also start from any public repository you want or use any code you find anywhere.

#### Assessment criteria
* Work with git
* Code readability
* Code maintainability
* Solution simplicity - solve only the task itself don't do any extra stuff that is not explicitly required
* Solution correctness - it does what it promise to do
* Discussion over solution

#### What is not important
* Prediction error - do not spend much time on prediction itself, predicting bitcoin price is very hard task, if we could solve it we would be millionares - solution like "average from last three minute prices" is completely OK. You are free to use whichever method you want for prediction but this won't be important factor
* Solution performance - the API does not need to be able to return the answer fast nor it needn't to be able to process requests from many callers at once
