---
layout: post
title: Introduction To Dynamic Programming
---

![_config.yml]
### What is Dynamic Programming ?

Dynamic Programming refers to a very large class of algorithms. The idea is to break a large problem down (if possible) into incremental steps so that, at any given stage, optimal solutions are known to sub-problems. When the technique is applicable, this condition can be extended incrementally without having to alter previously computed optimal solutions to subproblems. Eventually the condition applies to all of the data and, if the formulation is correct, this together with the fact that nothing remains untreated gives the desired answer to the complete problem.

The simple example of dynamic programming is the solve of Fibbonacci Sequence which in <b>f(n) = F(n-1) + F(n-2) </b> Where F(0) = 0 & f(1) = 1 .

#### Ways to solve this types of Problem :
- Identify if it is a DP problem
- Decide a state expression with least parameters or the recurrence relation like 
- Formulate state relationship <b>f(n) = F(n-1) + F(n-2) </b>
- Do tabulation (or add memoization)
