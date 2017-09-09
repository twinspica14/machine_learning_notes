# machine_learning_notes
# covariance is matrix of var(x)var(x) var(x)var(y)
                        var(y)var(x) var(y)var(y)
                        
                        covariance indicates how both lines are intercorrelated to each other
                        
                        
## Pearson's coeffiecient for correlation between two variables. It helps us to predict the other variable. It's indicated by r or ro, r is for samples, and ro is for population
It ranges from -1 to 1
## http://onlinestatbook.com/2/describing_bivariate_data/pearson.html

# Probability Distribution
Bernoulli Distribution
E(x) = summation(xP(x))
bernoulli distribution is either 0 or 1,
where x is possible value for example 0P(0) + 1(P(1) -> 0(1-lambda) + 1(lambda)
E(x) = lambda ~ Mean

# Variance in terms of Expected value is E((X-mu)^2) -> (X-mu)^2 P(X)

## Binomial distribution is based upon burnolli distribution. So, if there is n trial, and the probability of it's occurenece is either 0 or 1, then
Over all probability is # b(x; n, P) = nCx * Px * (1 – P)n – x, where we have n independent trials.
so, it's mu = np(x), and variance is mu(1-p)

# Normal Distribution
# f(X)= (1/σ√2π)​e−((x−μ)^2)/2*σ^2) where σ is Standard distribution, and μ is mean.
  It's usaully bell shaped. 2 standard^2 also indicates width of the graph.
  (1/2π*(sigma)^1/n)*e-((x−μ)T*sigma^-1*(x−μ))/2 where sigma is covariance matrix
  
# Poisson Distribution
The Poisson Probability Distribution
The Poisson Distribution was developed by the French mathematician Simeon Denis Poisson in 1837.
The Poisson random variable satisfies the following conditions:

    The number of successes in two disjoint time intervals is independent.

    The probability of a success during a small time interval is proportional to the entire length of the time interval.

Apart from disjoint time intervals, the Poisson random variable also applies to disjoint regions of space.
The probability distribution of a Poisson random variable X representing the number of successes occurring in a given time interval or a specified region of space is given by the formula:

    link for more explanation with formula https://www.intmath.com/counting-probability/13-poisson-probability-distribution.php
   
   
  
 # Bayer's Theorem
 we use P(X) when no other information is given, but as we collect more information we prefer to go with bayer's theorem.
 According to bayer's theorem we should use conditional probability at this moment.
 P(A|B) = P(A ⋂ B)/ P(B)
 often we are give P(B|A) are requested to find P(A|B) = P(A ⋂ B)/ P(B) or P(A|B)P(B)/P(A)
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
