# Problems level:1.1
## Dynamic Programming problems

- Matrix Chain Multiplication
        Given an array p[] which represents the chain of matrices such that the ith matrix Ai is of dimension p[i-1] x p[i]. We need to write a function MatrixChainOrder() that should return the minimum number of multiplications needed to multiply the chain.
- 0-1 Knapsack Problem
        Given two integer arrays val[0..n-1] and wt[0..n-1] which represent values and weights associated with n items respectively. Also given an integer W which represents knapsack capacity, find out the maximum value subset of val[] such that sum of the weights of this subset is smaller than or equal to W. You cannot break an item, either pick the complete item, or don’t pick it (0-1 property).
- Travelling salesman problem
        Given a set of cities and distance between every pair of cities, the problem is to find the shortest possible route that visits every city exactly once and returns to the starting point.
- Perfect Sum Problem (Print all subsets with given sum)
        Given an array of integers and a sum, the task is to print all subsets of given array with sum equal to given sum.
        Input : arr[] = {2, 3, 5, 6, 8, 10}
        sum = 10
        Output :    5 2 3
                    2 8
                    10
- Longest Repeated Subsequence
        Given a string, print the longest repeating subsequence such that the two subsequence don’t have same string character at same position, i.e., any i’th character in the two subsequences shouldn’t have the same index in the original string.
        Input: str = "aabb"
        Output: "ab"
        Input: str = "aab"
        Output: "a"