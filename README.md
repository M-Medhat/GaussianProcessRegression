Gaussian Process (GP) Regression in Julia
===

This is a simple, one-dimentional regression using Gaussian Process. It's implemented in  [Julia](http://julialang.org/). The original implementation using Python and SciKit-Learn can be found [here](http://scikit-learn.org/0.11/auto_examples/gaussian_process/plot_gp_regression.html)

###Directory Structure
* **GP**: Contains Code for Gaussian Process Implementation
 * **GP/GP.jl**: GP Module.
 * **GP/covariance.jl**: Covariance implementation (Squared Exponential) .
 * **GP/predict.jl**: Prediction using GP.
* **GaussianProcesRegression.jl**: Implementation of the regression and generation of figures.
* **README.md**: This file.

###Gaussian Process Implementation
The code for the gaussian process is written by **Peter Schulam** ([github](https://github.com/pschulam-attic/GP.jl))