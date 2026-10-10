## Machine Problem 6

Given an array of N integers, answer Q queries. Each query contains two indices L and R. Print the sum of the elements from index L to index R, inclusive.


Input: The first line contains two integers N and Q. The second line contains N space-separated integers representing the array. Each of the next Q lines contains two integers L and R.

Output: For each query, print the sum of the elements in the specified range.

Constraints
- 1 <= N, Q <= 200000
- -10^9 <= A[i] <= 10^9
- 1 <= L <= R <= N

Sample Input:
```
5 3
2 4 1 7 3
1 3
2 5
3 3
```
Sample Output:
```
7
15
1
```
