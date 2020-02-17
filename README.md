# MIE1516_A2_Gibbs_sampling
Algorithm: 
1. Initialize 
* Set evidence to restriction, i.e. for $P(S|R=1)$ set all factors to $R=1$ where $R$ shows up. 
* Set all other variables to random values between 1 or 0. 

2. Repeat the following for some number of iterations 
* Choose a non-evidence variable. 
* Get all the factors that cointain the current non-evidence variable.
  * The numerator wil be the product of all of these factors with the replaced values based on the random assignment except for the replacement of the non-evidence variable. This should give you a single probability number. 
  * The denominator will be the same product as above except marginalized by the current non-evidence variable. 
  
* Sample this variable on nothing else changing. 


### References
http://www.mit.edu/~ilkery/papers/GibbsSampling.pdf

