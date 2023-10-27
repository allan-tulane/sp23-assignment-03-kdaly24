# CMPS 2200 Assignment 3
## Answers

**Name:**____Killian Daly_______


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

Recursion for iterative solution is $W(n) = W(n-1) + 1$ , as iterative executes parens update for each item of N through the whole list.

Span is $S(n-1) + 1$

The Big O solution for work is $O(n)$

Span is also $O(n)$




- **d.**

Recursion for Work is $W(n) = W(n/2) + n$, to account for the functions list mapping, as well as the scan and reduce at each level

Span is $S(n) = S(n/2) + 1$. 

Big O solution for Work is $O(n)$, as function is root dominated

Span is $O(\log n)$




- **f.**

Recursion for Work is $W(n) = 2W(n/2) + 1$

Span is $S(n/2) + 1$ as we only care about one branch

Big O solution for Work is $O(n)$

Span is $O(\log n)$