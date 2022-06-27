
# Shrinkage Methods

## Questions

1. **Which one is true?**

    (A) Ridge and Lasso regression are techniques to reduce the model complexity and prevent over-fitting which may result from simple linear regression

    (B) Ridge regression shrinks the coefficients, and it helps to reduce the model complexity

    (C) Lasso regression not only helps in reducing overfitting, but it can help us in feature selection

    (D) All of the above


1. **What is true about ridge regression?**

    (A) When lambda is 0, the model works like linear regression model

    (B) When lambda is 0, the model doesn’t work like linear regression model

    (C) If lambda goes to infinity, we get very, very small coefficients approaching 0

    (D) If lambda goes to infinity, we get very, very large coefficients approaching infinity


1. Suppose we fit Lasso Regression to a data set, which has 100 features (X1,X2…X100). 
Now, we rescale one of these feature by multiplying with 10 (say that feature is X1), and then refit Lasso regression with the same regularization parameter.
**Now, which of the following option will be correct?**

    (A) It is more likely for X1 to be excluded from the model

    (B) It is more likely for X1 to be included in the model

    (C) Can’t say

    (D) None of these


## Answers

1. D

1. A and C

1. B - Big feature values ⇒smaller coefficients ⇒less lasso penalty ⇒more likely to have be kept

