## Machine Problem 8

Given an undirected, unweighted graph, find the minimum number of edges needed to travel from vertex S to vertex T. If no path exists between the two vertices, print -1.

Input: The first line contains two integers N and M. Each of the next M lines contains two integers U and V, representing an undirected edge. The last line contains two integers S and T, representing the starting and destination vertices.

Output: Print the minimum number of edges from S to T, or -1 if no path exists.

Constraints:
- 2 <= N <= 200000
- 1 <= M <= 300000
- 1 <= S, T <= N

Sample Input:
```
5 5
1 2
1 3
2 4
3 4
4 5
1 5
```

Sample Output:
```
3
```
