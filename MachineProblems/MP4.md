## Machine Problem 4

Create a program that finds and prints the equilibrium index of an array. An equilibrium index is a position in the array where the sum of all elements to its left is equal to the sum of all elements to its right. The element at the equilibrium index is not included in either sum.

If the equilibrium index is the first element, the sum of the left side is considered 0. If it is the last element, the sum of the right side is considered 0.

If no equilibrium index exists, the program should print -1.

Input: The first line contains an integer N, representing the size of the array. The second line contains N space-separated integers representing the array elements.

Output: Print the equilibrium index. If no equilibrium index exists, print -1.

Constraints:
- 1 ≤ N ≤ 10⁵
- -10⁹ ≤ A[i] ≤ 10⁹
- Time Limit: 1 second
- Memory Limit: 256 MB

Sample input:
```
7
-7 5 1 2 -4 3 0
```

Sample output:
```
3
```