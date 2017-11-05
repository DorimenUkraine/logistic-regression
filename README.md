# logistic-regression

### Please use the link provided in github to view the file with the external viewer *nbviewer*

This algorithm builds a model for logistic regression.

This model creates a dataset as follow :

<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;1&space;&&space;x_1\\&space;\dots&space;&&space;\dots\\&space;1&space;&&space;x_n&space;\end{pmatrix}" title="\begin{pmatrix} 1 & x_1\\ \dots & \dots\\ 1 & x_n \end{pmatrix}" />

where <img src="http://latex.codecogs.com/gif.latex?(x_1,&space;x_2,\dots,x_n)&space;\in&space;\{0,1\}" title="(x_1, x_2,\dots,x_n) \in \{0,1\}" />

![Generated data](https://raw.githubusercontent.com/cheillanju/logistic-regression/master/dataset.png)

It uses the cross-entropy loss function that I need to minimize with gradient descent algorithm.

I use dot product between coefficients and x values.
To speed up the gradient descenter, I use Nadam optimizer. It allows to get a better curve as well.

Once I get our coefficients approximation, I plot the cumulative distribution function to get probabilities.

![Result](https://raw.githubusercontent.com/cheillanju/logistic-regression/master/result.png)
