***1 Distributions of Two Random Variables***
(Random Vector). Given a random experiment with a sample space C, consider two random variables X1 and X2, which assign to each element c of C one and only one ordered pair of numbers X1(c) = x1, X2(c) = x2. Then we say that (X1,X2) is a random vector. The space of (X1,X2) is the set of ordered pairs D = {(x1, x2) : x1 = X1(c), x2 = X2(c), c ∈ C}.

We say a random vector (X1,X2) with space D is of the continuous type if its cdf FX1,X2(x1,x2) is continuous.

We may extend the definition of a pdf fX1,X2(x1,x2) over R2 by using zero elsewhere. 

Let (X1, X2) be a random vector. Then both X1 and X2 are random variables. We can obtain their distributions in terms of the joint distribution of (X1,X2) as follows.

In general, because these distributions are recorded in the margins of the table, we often refer to them as marginal pmfs.

Hence, in the continuous case the marginal pdf of X1 is found by integrating out x2. Similarly, the marginal pdf of X2 is found by integrating out x1.

2 Transformations: Bivariate Random Variables.  

3 Conditional Distributions and Expectations
In this section, we discuss conditional distributions, i.e., the distribution of one of the random variables when the other has assumed a specific value. 

We discuss this first for the discrete case, which follows easily from the concept of conditional probability presented in Section
We call pX2 |X1 (x2 |x1 ) the conditional pmf of the discrete type of random variable X2, given that the discrete type of random variable X1 = x1.

That is, fX2|X1 (x2|x1) has the properties of a pdf of one continuous type of random variable. It is called the conditional pdf of the continuous type of random variable X2, given that the continuous type of random variable X1 has the value x1. 

4 The Correlation Coefficient(相关系数)   
It should be noted that the expected value of the product of two random variables is equal to the product of their expectations plus their covariance; that is, E(XY ) = μ1μ2 + ρσ1σ2 = μ1μ2 +cov(X,Y).

5 Independent Random Variables   

6 Extension to Several Random Variables


E is a linear operator
f2,...,n|1(x2,...,xn|x1) is called the joint conditional pdf of X2,...,Xn, given X1 = x1.
In addition, if several random variables are mutually independent and have the same distribution, we say that they are independent and identically dis- tributed, which we abbreviate as iid.

6.1 ∗Multivariate Variance-Covariance Matrix

Let X = (X1, . . . , Xn)′ be an n-dimensional random vector. Recall that we defined E(X) = (E(X1), . . . , E(Xn))′, that is, the expectation of a random vector is just the vector of the expectations of its components. Now suppose W is an m × n matrix of random variables, say, W = [Wij] for the random variables Wij, 1 ≤ i ≤ m and 1 ≤ j ≤ n.

Let X = (X1, . . . , Xn)′ be an n-dimensional random vector, such that σi2 = Var(Xi) < ∞. The mean of X is μ = E[X] and we define its variance-covariance matrix to be,
Cov(X) = E[(X − μ)(X − μ)′] = [σij ],
where σii denotes σi2. As Exercise 2.6.8 shows, the ith diagonal entry of Cov(X) is σi2 = Var(Xi) and the (i,j)th off diagonal entry is Cov(Xi,Xj). So the name, variance-covariance matrix is appropriate.

7 Transformations for Several Random Variables.  
8 Linear Combinations of Random Variables.   
