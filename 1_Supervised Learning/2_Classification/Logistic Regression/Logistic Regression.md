# LOGISTIC REGRESSION:

Logistic regression does not offer the same features as linear regression. The former offers a prediction about a binary category. There are other types of logistic regression, including binary classification, multinomial or multiclass classification and ordinal classification:

• Binary Classification: which involves having one category.
• Multinomial Classification: which involves having more than one category.
• Ordinal Classification: which involves ordered categories, useful if we wanted to order our outcomes

Remember how linear regression worked better with more correlated variables? Logistic regression is the opposite - the variables don't have to align. That works for this data which has somewhat weak correlations.

Logistic regression relies on the concept of 'maximum likelihood' using sigmoid functions. A 'Sigmoid Function' on a plot looks like an 'S' shape. It takes a value and maps it to somewhere between 0 and 1. Its curve is also called a 'logistic curve'. Its formula looks like 

- h = 1 / 1+e^-z
- z = 0X

 where the Sigmoid midpoint finds itself at x's 0 point, L is the curve's maximum value, and k is the curve's steepness. If the outcome of the function is more than 0.5, the label in question will be given the class '1' of the binary choice. If not, it will be classified as '0'.
 