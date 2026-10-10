## Machine Problem 5

A warehouse maintains a sorted list of product IDs to keep track of its inventory. Each product has a unique integer ID, and all IDs are arranged in ascending order.

Your task is to develop a program that searches for a specific product ID in the inventory. The program must determine whether the target ID exists in the list and display its index if found.

Input: The first line contains an integer N, representing the number of product IDs. The second line contains of distinct integers sorted in ascending order. The third line contains an integer X, representing the product ID to search for.

Output: If the product ID exists, print Found at index i, where i is the zero-based index of the product ID. If the product ID does not exist, print Product not found.

Constraints: 
- Time Limit: 1 second
- Memory Limit: 256 MB


Sample Input: 

```
8
10 20 30 40 50 60 70 80
30
```

Sample Ouput:
```
2
```