****Probability and Distributions    
***1.Introduction

Many kinds of investigations may be characterized in part by the fact that repeated experimentation,   
under essentially the same conditions, is more or less standard procedure.  
But it is characteristic of these experiments that the outcome cannot be predicted with certainty prior to the performance of the experiment.  
__random experiment__:   
1⃣️ a collection of every possible outcome can be described prior to its performance  
2⃣️ this kind of experiment can be repeated under the same conditions  
__sample space__: the collection of every possible outcome  
__relative frequency__: The ratio f/N is called the relative frequency of the event C in these N experiments.  
the number _f_ of times (the __frequency__).  
The ratio _f/N_ is called the __relative frequency__.  
But as N increases, experience indicates that we associate with the event C a number, say p, that is equal or approximately equal to that number about which the relative frequency seems to stabilize.   
Thus, although we cannot predict the outcome of a random experiment, we can, for a large value of N, predict approximately the relative frequency with which the outcome will be in C.   
_p_ would be called the __probability__ of the event _C_.  

The preceding interpretation of probability is sometimes referred to as the relative frequency approach, and it obviously depends upon the fact that an experiment can be repeated under essentially identical conditions.

*** 2. Set Theory  
Accordingly, in describing our sets, we frequently speak of a set of points (a set whose elements are points).  
The notation C = {x : 0 ≤ x ≤ 1} is read “C is the one-dimensional set of points x for which 0≤x≤1.”   
Similarly,C={(x,y):0≤x≤1,0≤y≤1}can be read“C is the two-dimensional set of points (x,y) that are interior to, or on the boundary of, a square with opposite vertices at (0, 0) and (1, 1).”
__subset__ C2 ⊂ C1
__null set__ C = φ. 
The set of all elements that belong to at least one of the sets C1 and C2 is called the __union__ of C1 and C2 __C1 ∪ C2__.  
The set of all elements that belong to each of the sets C1 and C2 is called the __intersection__ of C1 and C2  __C1 ∩ C2__.   
__Venn diagrams__  
In certain discussions or considerations, the totality of all ele- ments that pertain to the discussion can be described. This set of all elements under consideration is given a special name. It is called the space. We often denote spaces by letters such as C and D.  
Let C denote a space and let C be a subset of the set C. The set that consists of all elements of C that are not elements of C is called the comple- ment of C (actually, with respect to C)

__DeMorgan’s Laws__  

__set functions__  

***3 The Probability Set Function

We denote this collection of events by B. Technically, such a collection of events is called a σ-field of subsets.   
在数学中，某个集合X上的σ代数（σ-algebra）又叫σ域 ，是X的所有子集的集合（也就是幂集）的一个子集。这个子集满足对于可数个集合的并集运算和补集运算的封闭性（因此对于交集运算也是封闭的）。  
A collection of events whose members are pairwise disjoint is said to be a mutually exclusive collection.  
Let C be a sample space and let B be the set of events. Let P be a real-valued function defined on B. Then P is a probability set function if P satisfies the following three conditions:

__equilikely case  Counting Rules__  
multiplication rule or the mn-rule. 
We call each such k-tuple a __permutation__ and use the symbol Pkn to denote the number of k permutations taken from a set of n elements.   
We often use the terminology combinations instead of subsets. So we say that there are 􏰍n􏰎 __combinations__ of k things taken from a set of n things.   
we said that a sequence of events {Cn} is a nondecreasing sequence if Cn ⊂ Cn+1

***4 Conditional Probability and Independence***  
In some random experiments, we are interested only in those outcomes that are elements of a subset C1 of the sample space C. This means, for our purposes, that the sample space is effectively the subset C1. We are now confronted with the problem of defining a probability set function with C1 as the “new” sample space.   

Once defined, this probability is called the __conditional probability__ of the event C2, relative to the hypothesis of the event C1, or, more briefly, the conditional probability of C2, __given__ C1.   

Since C1 is now the sample space, the only elements of C2 that concern us are those, if any, that are also elements of C1, that is, the elements of C1 ∩ C2. It seems desirable, then, to define the symbol P(C2|C1) in such a way that
P (C1|C1) = 1 and P (C2|C1) = P (C1 ∩ C2|C1).   
Let C1 and C2 be two events. We say that C1 and C2 are independent if P (C1 ∩ C2) = P (C1)P (C2). __P (C2|C1) = P (C2)__.  
Suppose now that we have three events, C1, C2, and C3. We say that they are mutually independent if and only if they are pairwise independent:
P(C1 ∩ C3) = P(C1)P(C3), P(C1 ∩ C2) = P(C1)P(C2), P(C2 ∩C3)=P(C2)P(C3),
P(C1 ∩ C2 ∩ C3) = P(C1)P(C2)P(C3).

***5 Random Variables.*** 
The reader perceives that a sample space C may be tedious to describe if the elements of C are not numbers. We now discuss how we may formulate a rule, or a set of rules, by which the elements c of C may be represented by numbers.

Let X be a function such that X(T) = 0 and X(H) = 1. Thus X is a real-valued function defined on the sample space C which takes us __from the sample space C to a space of real numbers D = {0, 1}__.  

We call random variables of the first type discrete random variables, while we call those of the second type continuous random variables.  
Besides inducing the sample space D, X also induces a probability which we call the distribution of X.
pmf 离散型随机变量分布律 概率密度函数。 

The pmf of a discrete random variable and the pdf of a continuous random variable are quite different entities. The distribution function, though, uniquely determines the probability distribution of a random variable.   

shorten P({c ∈ C : X(c) ≤ x}) to P(X ≤ x).   
Let X and Y be two random variables. We say that X and Y are equal in distribution and write X =D Y if and only if FX(x) = FY (x), for all x ∈ R.   
As the next theorem shows, the discontinuities of a cdf have mass; that is, if x is a point of discontinuity of FX , then we have P (X = x) > 0.
 
***6 Discrete Random Variables***。 
We say a random variable is a discrete random variable if its space is either finite or countable    
As the last example suggests, probabilities concerning a discrete random vari- able can be obtained in terms of the probabilities P(X = x), for x ∈ D. These probabilities determine an important function, which we define as   

(Probability Mass Function (pmf)). Let X be a discrete random variable with space D. The probability mass function (pmf) of X is given by
pX(x) = P[X = x], for x ∈ D.

We have a random variable X and we know its distribution. We are interested, though, in a random variable Y which is some transformation of X, say, Y = g(X).

In the first case, g is one-to-one. Then, clearly, the pmf of Y is obtained as
pY (y) = P[Y = y] = P[g(X) = y] = P[X = g−1(y)] = pX(g−1(y)).   

The second case is where the transformation, g(x), is not one-to-one. Instead of developing an overall rule, for most applications involving discrete random variables the pmf of Y can be obtained in a straightforward manner.

***7 Continuous Random Variables***   
We say a random variable is a continuous random variable if its cumulative distribution function FX(x) is a continuous function for all x ∈ R.  
Let X be a continuous random variable with a known pdf fX. As in the discrete case, we are often interested in the distribution of a random variable Y which is some transformation of X, say, Y = g(X). Often we can obtain the pdf of Y by first obtaining its cdf.    

These examples illustrate the cumulative distribution function technique.
The graph of F(x) is shown in Figure 1.7.2. We see that F(x) is not always continuous, nor is it a step function. Accordingly, the corresponding distribution is neither of the continuous type nor of the discrete type. It may be described as a mixture of those types.
 
 8 Expectation of a Random Variable  
 Sometimes the expectation E(X) is called the mathematical expectation of X, the expected value of X, or the mean of X. When the mean designation is used, we often denote the E(X) by μ; i.e, μ = E(X).
 
 (Expectation of a Constant). Consider a constant random variable, that is, a random variable with all its mass at a constant k. This is a discrete random variable with pmf p(k) = 1. Because |k| is finite, we have by definition that
E(k) = kp(k) = k.

9 Some Special Expectations
Let X be a random variable whose expectation exists. The mean value μ of X is defined to be μ=E(X).

Let X be a random variable with finite mean μ and such that E[(X−μ)2] is finite. Then the variance of X is defined to be E[(X−μ)2]. It is usually denoted by σ2 or by Var(X).

It is customary to call σ (the positive square root of the variance) the standard deviation of X (or the standard deviation of the distribution). 


