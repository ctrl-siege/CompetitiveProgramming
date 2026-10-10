## Machine Problem 1

Create a program that will detect if the internet connection is fast or slow where:

N>=85 = FAST
N<85 = SLOW

Include the average of the internet connection and add if it is fast or slow.

Input: The first line contains an integer N, representing the number of internet speed readings. The next N lines each contain an integer representing an internet speed reading.

Output: For each reading, print FAST if the value is greater than or equal to 85; otherwise, print SLOW. After all readings, print the average internet speed as an integer, rounded down if the average is not a whole number. On the next line, print FAST if the average is greater than or equal to 85; otherwise, print SLOW.

Constraints:
- 1 ≤ N ≤ 10⁵
- 0 ≤ Speed ≤ 10⁹
- Time Limit: 1 second
- Memory Limit: 256 MB

Sample Input: 

```
6
134
56
78
90
100
123
```

Sample Output: 

```
FAST
SLOW
SLOW
FAST
FAST
FAST
96
FAST
```