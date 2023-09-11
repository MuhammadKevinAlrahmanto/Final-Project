# Final Project

This repository contains projects about applied statistical learning in polymer science. The goal of this research is to use past experiment data to determine significant electrospinning parameters affecting nanofiber quality (the diameter and smoothness of the fiber).

Just refer to the results on multiple linear regression and logistic regression. The regression diagnostic and the Wald test reveal the significance of the parameters.

Another important note on polynomial regression is that while we can get high r-squared values, but the risk of overfitting is extremely high. 

The data used in this project is less than 50 observations, the ratio of observations to the number of dependent variables is in the single digits (33/8). So it's wise enough if we don't try to extrapolate the model!
 
However, I am still happy with the results of multiple linear regression. The QQ plot confirms that there is normality in the residuals. Multiple linear regression is easy to interpret. Use the partial derivative in the final model equation and voila - assuming another variable remains constant, we can get the relationship between the input variables and output variable.

If we want to use this result for future experiments, please take a look at the descriptive statistics. This model should be interpreted within the range of the available data itself (INTERPOLATION).
