---
{"dg-publish":true,"permalink":"/10-19-personal-management/12-learning/12-02-pomona-college/math-103-combinatorics/lecture-1/","tags":[" #pomona/courses"," #pomona/math"]}
---


# A. Introduction

Combinatorics is the mathematics of discrete / finite structures. For example, consider the following sets: 
$$ 
\begin{aligned}
S_1 &= \{\text{paths from } A \text{ to } B \text{ in a maze} \} \\
S_2 &= \{\text{ways to complete a Sudoku grid} \} \\
S_3 &= \{\text{anagrams of MISSISSIPI} \} \\
S_4 &= \{\text{colorings of a map} \} 
\end{aligned}
$$

Common questions that one may consider when contemplating these sets:
1. Are there any? Is the set non-empty or empty?  $S_1 \stackrel{?}{=} \emptyset$
2. How many are there? Is the set finite? $|S_2| = 1 \text{ and } |S_3| = 34,650$
3. What's the best one? ("best" with respect to some ordering, e.g., the shortest path, or the coloring using the fewest colors)
4. How can we find one? How can we find the best one? 

Right now, we will mostly work with question 2. We will learn general principles:

- induction
- pigeonhole principle
- counting by telling the same story in 2 different ways
- inclusion / exclusion principle
- generating functions

and see examples of ad hoc methods to solve these problems. 

## A.1. What does "counting" mean?

The best case is to have a closed formula to determine the number of items in a set. 

> [!example]
> **How many dots are there in a triangle of side $n$?**
> 
