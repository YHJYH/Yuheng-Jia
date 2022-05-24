---
layout: default
---
# Schaum's outlines of probability and statistics
## Part I: probability
### Chapter 1 basic probability
mutually exclusive: $P(A_{1}\cup A_{2})=P(A_{1})+P(A_{2})$. 

not mutually exclusive: $P(A_{1}\cup A_{2})=P(A_{1})+P(A_{2})-P(A_{1}\cap A_{2})$ . 

**Bayes' theorem**: 
$$P(A_{k}|A) = \frac{P(A|A_{k})P(A_{k})}{\sum_{j=1}{P(A|A_{j})P(A_{j})}}$$

**permutation**:
- order of *r* does matter
- number of permutations of *n* different objects taken *r* at a time: nPr
- when r=n, nPn=n! (n *factorial*)
- in circular permutation, a place holder is stationary, so number of ways is (n-1)!

**combination**:
- order of *r* does not matter
- when r=n, nCn=1
- nCr = nCn-r
- used as **binomial coefficients** in **binomial expansion**.
- the probability of getting *x* As in *n* independent trials is: nCx$p^{x}q^{n-x}$

Probability using combinational analysis: 注意是否**in order**, 如果not in order则用combination, in order用permutation。见Problem 1.35 (e)(f).

**Stirling's approximation** to *n!*: $n! \approx \sqrt{2\pi n}n^{n}e^{-n}$

Poker cards: suits(spades黑桃♠, heart红心♥, diamonds方片♦, clubs梅花♣), rank(ace A, 2-10, jack J, queen Q, king K).<br>




[back](../)
