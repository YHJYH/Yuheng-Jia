---
layout: default
---
# Schaum's outlines of probability and statistics
## Part I: probability
- [Chapter 1 basic probability](https://github.com/YHJYH/Yuheng-Jia/blob/main/subsec/schaums.md#chapter-1-basic-probability)
- [Chapter 3 mathematical expectation](https://github.com/YHJYH/Yuheng-Jia/blob/main/subsec/schaums.md#chapter-3-mathematical-expectation)
### Chapter 1 basic probability
**mutually exclusive**: $P(A_{1}\cup A_{2})=P(A_{1})+P(A_{2})$. 

not mutually exclusive: $P(A_{1}\cup A_{2})=P(A_{1})+P(A_{2})-P(A_{1}\cap A_{2})$ . 

**Bayes' theorem**: 
$$P(A_{k}|A) = \frac{P(A|A_{k})P(A_{k})}{\sum_{j=1}{P(A|A_{j})P(A_{j})}}$$
application: [coin flip sequence](https://dspace.mit.edu/bitstream/handle/1721.1/70477/6-042j-fall-2002/contents/lecture-notes/cp10Fsol.pdf)

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
- the probability of getting *x* As in *n* independent trials is: nCx p^{x}q^{n-x} (**binomial distribution**, Problem 1.37, 1.81)
- Case study: 
    1. [# shortest paths on grid](https://betterexplained.com/articles/navigate-a-grid-using-combinations-and-permutations/)
    2. [# new word from given letters](https://brainly.in/textbook-solutions/q-number-i-combinations-1?source=qa-qp-match#q-number-permutations-letters-letters-word-tennessee)


Probability using combinational analysis: 注意是否**in order**, 如果not in order则用combination, in order用permutation。见Problem 1.35 (e)(f).

**Stirling's approximation** to *n!*: $n! \approx \sqrt{2\pi n}n^{n}e^{-n}$.

Poker cards: suits(spades黑桃♠, heart红心♥, diamonds方片♦, clubs梅花♣), rank(ace A, 2-10, jack J, queen Q, king K).<br>

### Chapter 3 mathematical expectation
**Theorems of expectation**:
1. E[cX] = cE[X]
2. <img src="https://render.githubusercontent.com/render/math?math={\color{white}\L = -\sum_{j}[T_{j}ln(O_{j})] + \frac{\lambda W_{ij}^{2}}{2} \rightarrow \text{one-hot} \rightarrow -ln(O_{c}) + \frac{\lambda W_{ij}^{2}}{2}}">

[back](../)
