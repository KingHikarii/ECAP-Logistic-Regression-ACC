# ECAP-Logistic-Regression-ACC

Logistic Regression is a statistical model that was developed in the field of statistics for binary classification problems. It gives an output of either 0 or 1.

It was developed in order to calculate the growing population rate within an enviroment that has limited resources.

Logistic Regression gets its name from its core function which is called as either the logistic function or the sigmoid function. The logistic function is an S-shaped curve that can take any real number and map it unto a value between 0 and 1 but never at those limits.Logistic Regression.png

Representation Behind Logistic Regression

It is just like the linear regression where the equation is its representation, the input values (x) are combined linearly using weights to predict an output (y). However the key difference is the predicted output will give us a binary value 0 or 1 rather than a continuous numerical value. The logistic regression equation can be expressed as the following: Logistic Regression Equation.png

P(y = 1|x) represent the probability of the positive class.
The betas are the model's coefficients (weights) learned during training, while B0 is the bias
The (x)s are the input features.
Logistic Regression Predicts Probabilities

Logistic regression models the probability of the default class (e.g the 1st class). For example, if we modelling people's sex as male or female from their height, then we can make the default class a male and the other class as female. Logistic regression will then predict that a given person is male baased off their height. This can then be written as P ( y = 1 | height ), where 1 is male and 0 is for female.

In conclusion, logistic regression predicts probabilities. It is used for classification and estimating probabilities. It is a powerful classification technique technique that estimates the likelihood of an input belonging to a partificular class.

Learning the Logistic Regression

In logistic regression, we use the maximum likelihood to estimate the coefficients (beta values B) from our training input. If our model is predicting a value very close to 1 for the default class and a value close to 0 for the other class, then it means we are getting better coefficients.

The intuition for maximum likelihood for logistic regression states this:

"The search procedure seeks values for the coefficients that minimizes the errors in the probabilities predicted by the model."
