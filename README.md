# Piecwise-Linear-Model-For-Nonconvex-Classifiers
Classifier for a two-class dataset using only piecewise linear functions. Applicable to any nonlinear non-convex boundary of moderate complexity.

## MATLAB files description
`demo_pwl.m`: This is the main file which loads (different kind of) data file and divides it into training and testing set. Then it calls the `run_sequentially.m` file after setting the parameter m which denotes the number of piecwise linear components in the classifier. 

`run_sequentially.m`: This file calls the `pwl_classifer.m` for each value of $m$ 

