# Assignment-6

**Team Members**
|   Enrollment No.  |   Name   | GithubId |
|   --------------  |   ----   | -------- |
|    IIT2019225  |   Kishan Tripathi | GhostFoxSledgehammer |
|    IIT2019226  |   Mukul Mohmare | Mu-C00L | 
|    IIT2019227  |   Anshuman Bhardwaz | anshumanbhardwaj1370  |

**Group No-**"14"

**Faculty Name-**"Dr. Rahul Kala"

**Mentor Name-** "Md. Meraz"

---
## Problem Statement
0/1 Knapsack Problem

---
## How to use code
```
Download project
https://github.com/GhostFoxSledgehammer/daa.git
```
Project Initialize 
```
#Opening Assingment folder
cd assingment2

#Compiling The code
g++ code.cpp -o solution
```
---

Run the code
```
./solution
```
Input
```
Input contains an line with 2 numbers w and n, where w is the max capacity and n is no. of items. Next n lines contain value and wieght for each item.
```
Ouput 
```
Output will be the maximum value.
```
---
---
*Test case*
```
Input:
50 3
60 10
100 20
120 30

Output:
220
```
### Theory
Logic
```
The maximum value that can be obtained
from n items is the max of following two values.
1. Maximum value obtained by n-1 items and W
weight (excluding nth item).
2. value of nth item plus maximum value obtained
by n-1 items and W minus weight of the nth
item (including nth item).
If the weight of the nth item is greater than W, then
the nth item cannot be included and case 1 is the
only possibility
```

---
###Analysis

*Time Complexity*
```
Time Complexity – O(n * w)

Space Complexity – O(n * w)
```

---
### References
```
https://www.geeksforgeeks.org/0-1-knapsack-problem-dp
https://www.geeksforgeeks.org/space-optimized-dp-solution-?ref=rp
https://www.educative.io/blog/0-1-knapsack-problem-dynamic-https://www.educative.io/courses/
grokking-dynamic-programming-patterns-for-coding-interviews/RM1BDv71V60
```