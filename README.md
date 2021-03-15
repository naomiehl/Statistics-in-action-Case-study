# Statistics_Case_Study_2
MAP566 -  Statistics in Action

## Preliminary comments:

* diagnostic plots are always welcome
* Bayesian Information Criteria (BIC) will be used for comparing models


## 1 Fitting a linear model (*)
The file sales1.csv consists of quarterly sales volumes (in % and indexed to the time 0) of a product.

* Plot the data
* Fit a polynomial model to this data (justify the choice of the degree). What do the residuals suggest?
* Try to improve the model by adding a periodic component. Write your final model as a mathematical equation.
Hints: cos(2πt/T) and sin(2πt/T) are periodic functions of period T.
One can easily deduce the period T from the context and looking at the data…

* Plot on a same graph the observed sales together with the predicted sales given by your final model. What do you think about this model? What about the residuals?
* We want the predicted sales volume to be equal to 100 at time 0. Modify your final model in order to take this constraint into account.


## 2 Fitting a linear mixed effects model (**)

* The file sales30.csv now consists of quarterly sales volumes (still in % and indexed to the time 0) of 30 different products.

* Plot the data
* Fit the model used previously for fitting the first series to this data and comment the results.
* Fit a mixed effect model to this data (discuss the choice of fixed and random effects). Write your final model as a mathematical equation.
* Plot the data with the predicted sales given by your final model.
* How could you take into account the previous constraint (predicted sales volume are all equal to 100 at time 0)?


## 3 Individual prediction (***)

* The file salesNew.csv consists of quarterly sales volumes of another product.

* The final model of part 2 will be used here. In other words, you should not use the new data to fit any new model.

* Suppose first that we don’t have any data for this product (although data are available for this product, we act as if we do not know them). How can we predict the sales volumes for this product? plot the data and the prediction on a same graph.

* Suppose now that only the first data at time 1 is available for this product. Compute and plot the new predictions.

* Repeat the same process with an increasing number of observed data. Comment the results.
