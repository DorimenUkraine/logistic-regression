# logistic-regression

### Please use the link provided in github to view the file with the external viewer *nbviewer*

This algorithm builds a model for logistic regression.

This model creates a dataset as follow :

<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;1&space;&&space;x_1\\&space;\dots&space;&&space;\dots\\&space;1&space;&&space;x_n&space;\end{pmatrix}" title="\begin{pmatrix} 1 & x_1\\ \dots & \dots\\ 1 & x_n \end{pmatrix}" />

It uses the cross-entropy loss function that we need to minimize with gradient descent algorithm.

We use dot product between coefficients and x values.

Once we get our coefficients approximation, we plot the cumulative distribution function to get probabilities.
