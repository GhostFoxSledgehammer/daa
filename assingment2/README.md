# Assignment-1

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
Longest Repeating Subsequence

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
g++ lrs.cpp -o solution
```
---

Run the code
```
./solution
```
Input
```
Input contains an string S.
```
Ouput 
```
Output will bethe longest repeating subsequence.
```
---
---
*Test case*
```
Input:
ATACTCGGA

Output:
ATCG
```
### Theory
Logic
```
For this problem , the main idea is to find the subsequence which is repeating  for the longest length and with the restriction that when both the characters are same, they shouldn’t be on the same index in the two strings. 
We first prepare a table which stores longest common subsequence  between the given string and a copy of the same string but this time we need to keep a check that  when both the characters are same, they shouldn’t be on the same index in the two strings. 
```

---
###Analysis

*Time Complexity*
```
Time Complexity – O(nˆ2)

Space Complexity – O(nˆ2)
```

---
### References
```
https://www.geeksforgeeks.org/longest-repeated-subsequence/
https://www.techiedelight.com/longest-repeated-subsequence-problem/
https://www.geeksforgeeks.org/longest-repeating-subsequence/
```