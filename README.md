# Logistic_regression_SGD_without_sklearn
I initialized the weight_vector and intercept term to zeros in the initialize_weights() function.

I created a loss function in the logloss() function to calculate the log loss.

For each epoch:
a. For each batch of data points in the training set (with a batch size of 1), I calculated the gradient of the loss function with respect to each weight in the weight vector using the gradient_dw() function.
b. I also calculated the gradient of the intercept using the gradient_db() function.

I updated the weights and intercept using the equation mentioned in the provided PDF (equation number 32).

After updating the weights and intercept, I calculated the log loss for the training and test sets using the updated weights. This step can be done by referring to the Python assignment question 10.

If desired, I compared the previous loss with the current loss. If the loss did not update significantly, I could stop the training.

I appended the calculated loss for each epoch to a list. This list can be used to observe how the loss changes over the course of training.
