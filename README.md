# Python Implementation of Hierarchical Dirichlet Processes
-----------------
Repository for final STA 663 project on Hierarchical Dirichlet Processes

This package implements the Hierarchical Dirichlet Process (HDP) described by [Teh, et al (2006)](https://sakai.duke.edu/access/content/group/c96b451b-2a44-447f-b8dc-956611b1acec/Final_Project_Papers/Hierarchical%20Dirichlet%20Processes.pdf), a Bayesian nonparametric algorithm which can model the distribution of grouped data exhibiting clustering behavior both within and between groups.  We implement two different Gibbs samplers in Python to approximate the posterior distribution over the parameters of an HDP mixture model.  Although the HDP is flexible enough to model most any data-generating distribution, we currently support two conjugate models: (1) a Poisson and (2) a multinomial likelihood, with a gamma and Dirichlet prior over their respective parameters.  There is also a more optimized categorical model (a special case of the multinomial case).


## Installation
----------------
To install the package, use `python setup.py install`.

The following prerequisites are required (the package versions shown were those used in development):


## Authors
----------------
+ Quinn Frank
+ Morris Greenberg
+ George Lindner

This project was made for STA 663 (Spring, 2020) at Duke University.


