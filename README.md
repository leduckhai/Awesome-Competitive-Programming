# Awesome Competitive Programming Problems

This repository contains my implementation of useful **data structures**, **algorithms** and **solutions** for some awesome competitive programming problems in Hackerrank and Project Euler

I create this for faster implementation in interviews and programming contests

Written in Python 3

How to use
----------
- [x] : Useful data structures or algorithms

- [ ] : Solutions for some awesome competitive programming problems

**Mathematics** : Type of the Algorithm

**Permutation Problems** : Category of the Problem

[Lexicographic Permutations](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lexicographic_Permutations.ipynb) : Name of the problem

```
Awesome-Competitive-Programming 
│   README.md 
│
└───Folder 1        : Type of Algorithm 
│   │   File1.ipynb : Python codes for the problem
│   │   File1.pdf   : Descriptions and solution guides for the problem
│   │   ...   
│   
└───Folder 2
│   │   File2.ipynb
│   │   File2.pdf
│   │   ...
│
└───...    
```

Algorithms
----------
### Binary Search Tree Algorithm
#### Binary Search Tree Algorithm Applications
1. [Prime Permutations](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Binary%20Search%20Tree%20Algorithm/Prime_Permutations.ipynb)
- [x] Find a Number of a Sorted List - **O(logn)**
- [x] Find the Index of a Number in a Sorted List - **O(logn)**

### String Algorithm
#### Suffix Tree - Suffix Array
1. - [x] [Suffix Array (Manber-Myers Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/String%20Algorithm/SuffixArray_ManberMyers.ipynb): Find suffix array of a string S based on Manber-Myers algorithm - **O(n.log(n))** , n = |S|

2. - [x] [Longest Common Prefix Array (Kasai Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/String%20Algorithm/LCPArray_Kasai.ipynb): Find longest common prefix array of a string S with the help of suffix array based on Kasai algorithm - **O(n)** , n = |S|

### Searching and Graph Algorithms
1. [Lily's Homework](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Lily's_Homework.ipynb)
- [x] Graph Representation using Adjacency List
- [x] Unweighted Graph
- [x] Breadth-First Search Shortest Path - **O(V+E)**

2. [Count Luck](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Count_Luck.ipynb)
- [x] Graph Representation using Adjacency List
- [x] Unweighted Graph (also for disconnected graph)
- [x] Breadth-First Search Shortest Path - **O(V+E)**

3. [Count Luck 2](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Count_Luck_2.ipynb)
- [x] Graph Representation using Adjacency Matrix
- [x] Un- and weighted Graph
- [x] Dijkstra Shortest Path (also for disconnected graph) - **O(E.log V)**

4. [KnightL on a Chessboard](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/KnightL_on_a_Chessboard.ipynb)
- [x] Graph Representation using Adjacency List
- [x] Unweighted Graph (also for disconnected graph)
- [x] Breadth-First Search Shortest Path - **O(V+E)**

5. [Connected Cells in a Grid](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Connected_Cells_in_a_Grid.ipynb)
- [x] Graph Representation using Adjacency List
- [x] Unweighted Graph (also for disconnected graph)
- [x] Connected Components
- [x] Breadth-First Search - **O(V+E) for Adjacency List**

6. [Red Knight's Shortest Path](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Red_Knight's_Shortest_Path.ipynb)
- [x] Graph Representation using Adjacency List 
- [x] Find all nodes in graph - **O(VE) for Adjacency List**
- [x] Find all paths between 2 nodes using Breadth-First Search - **NP-Hard**

### Greedy Algorithm
1. [Sherlock and The Beast](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Greedy%20Algorithm/Sherlock_and_The_Beast.ipynb)
- Find the "Decent Number" having n Digits ("Decent Number" has its digits to be only 3's and/or 5's; the number of 3's it contains is divisible by 5; the number of 5's it contains is divisible by 3; and it is the largest such number for its length)

2. [Largest Permutation](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Greedy%20Algorithm/Largest_Permutation.ipynb)
- Swap 2 digits of a number k times to get largest number - **O(n)**

### Dynamic Programming
#### Coin Change Algorithms
1. - [x] [Coin Change](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/CoinChange.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/The_Coin_Change_Problem.pdf)</sup>: How many ways to pay V money using C coins [C1,C2,...Cn] - **O(C.V)**

2. - [x] [Integer Partition](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/IntegerPartition.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Coin_Partitions.pdf)</sup>: How many ways to partition number N using [1,2,...N] numbers - **O(n<sup>1.5</sup>)**

#### Path Sum Problems
3. - [x] [Max Path Sum Triangle](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Max_PathSum_Triangle.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Maximum_Path_Sum.pdf)</sup>: Find Maximum Path Sum from Top to Bottom of a Triangle - **O(R)** , R is number of rows of the triangle

4. - [x] [Min Path Sum Matrix: Top-Left to Right-Bottom, Right and Down Moves](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Min_PathSum_Matrix.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/PE81_PathSum_2Ways.pdf)</sup>: Find Min Path Sum from Top-Left to Right-Bottom of a Matrix using Right and Down Moves - **O(R.C)** , R, C is length of row and column of the matrix

#### Subarray/Subsequence/Substring Problems

> Subsequence = Any subset of an array/string 
>
> Subarray = Contiguous subsequence of an array
>
> Substring = Contiguous subsequence of a string

5. - [x] [Max Subarray Sum (Kadane Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Max_SubarraySum.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/The_Maximum_Subarray.pdf)</sup>: Find Maximum Subarray Sum of an Array - **O(n)**

6. - [x] [Min Subarray Sum (Kadane Algorithm's Varient](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Min_SubarraySum.ipynb): Find Minimum Subarray Sum of an Array - **O(n)**

7. - [x] [Longest Common Subsequence (LCS)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/LongestCommonSubsequence.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Common_Child.pdf)</sup>: Find the longest string S, every character in S is also in S1 and S2 but in order - **O(|S1|.|S2|)**

8. - [x] [Longest Increasing Subsequence (Patience Sorting Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Longest_Increasing_Subsequence.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Longest_Increasing_Subsequence.pdf)</sup>: Find the Longest Increasing Subsequence of an Array List based on Patience Sorting Algorithm- **O(n.log(n))**

8. - [x] [Longest Common Substring (Longest Common Factor - LCF)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Longest_Common_Substring.ipynb): Find the Longest Common Substring (Factor) of 2 strings S1 and S2 - **O(|S1|.|S2|)** 

9. - [x] [Sum Of Substrings](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/SumOfSubstrings.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/SumOfSubstrings.pdf)</sup>: Find Sum of All Substrings of an Number String S - **O(|S|)**

### Mathematics
#### Binomial Coefficient Problems
1. - [x] [Pascal Triangle](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Pascal_Triangle.ipynb): Create Pascal Triangle (to Calculate Multiple Large-Number Combinations) - **O(n<sup>2</sup>)**

2. - [ ] [PE #15: Lattice Paths](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lattice_Paths.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lattice_Paths.pdf)</sup> : Find the number of routes from the top left corner to the bottom right corner in a rectangular grid

#### Factors Problems
3. - [x] [Factorization](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Factorization.ipynb): Find All Factors of a Number - **O(n<sup>1/2</sup>)**

#### Multiples Problems
4. - [ ] [PE #1: Multiples of 3 and 5](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Multiples_of_3_and_5.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Multiples_of_3_and_5.pdf)</sup>: Find Sum of Multiples of a Number - **O(1)**

#### Permutation Problems
5. - [x] [Lexicographic Permutations](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lexicographic_Permutations.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lexicographic_Permutations.pdf)</sup>: Find n-th Lexicographic Permutation of a very long Word - **O(n)**

6. - [x] [Permutation Check](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/arePermutations.ipynb): Check if 2 Numbers/Strings are Permutations - **O(n)** , n = max(|a|,|b|)

#### Primes Problems
7. - [x] ["Sieve Method" All Primes](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Sieve_All_Primes.ipynb): Find All Primes < n - **O(n<sup>1/2</sup>)**

8. - [x] [Primality Test (Common Method)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/isPrime.ipynb): Check if n is a Prime Number using "Common Method" - **O(n<sup>1/2</sup>)**

9. - [x] [Primality Test (Miller-Rabin)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/isPrime_Miller_Rabin.ipynb): Check if n is a Prime Number using Miller-Rabin Probabilistic Test - **O(k.log<sup>3</sup>n)** , k = \[1,2,...]

10. - [x] [Coprimes Check](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/areCoprimes.ipynb): Check if 2 Numbers are Coprime - **O(log a.b)**

#### Primes-Factors Problems
11. - [x] [Euler Totient Function (Number List)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Euler_Totient_NumList.ipynb): Find ALL Numbers of Coprimes < n based on Euler Totient Function - **O((l) + m.loglogm + l.(logm + k))** , k is the number of prime factors of n; m and l is max value and length of the input number list
      
12. - [x] [Euler Totient Function (Single Number)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Euler_Totient_SingleNum.ipynb): Find the Number of Coprimes < n based on Euler Totient Function - **O(n<sup>1/2</sup> + k)** , k is the number of prime factors of the input number n

13. - [x] ["Sieve Method" Smallest Prime Factors (SPF)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Sieve_SPF.ipynb): Find Smallest Prime Factors for All Numbers < N - **O(n.loglogn)** 
 
14. - [x] [Prime Factorization (Smallest Prime Factor)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PrimeFactorization_SPF.ipynb): Find All Prime Factors of a Number using Smallest Prime Factor (SPF) - **O(log n)** if a list of all Smallest Prime Factors from 0 to n available

15. - [x] [Prime Factorization](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PrimeFactorization.ipynb): Find All Prime Factors of a Number - **O(n<sup>1/2</sup>)**

#### Pythagorean Theorem
16. - [x] [Pythagorean Triplets Perimeter](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PythagoreanTriplets_Perimeter.ipynb): Find Pythagorean Triplets having Perimeter (or Sum) P - **O(P)**

17. - [x] [Pythagorean Triplets Less or Equal N](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PythagoreanTriplets_LessEqualN.ipynb): Generate all Pythagorean Triplets <= N - **O(N.log(N))**

#### Non-categorized
18. - [ ] [Number Spiral Diagonals](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Number_Spiral_Diagonals.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Number_Spiral_Diagonals.pdf)</sup>: Find Sum of Diagonals of Ulam Spiral Matrix

### Recursion


