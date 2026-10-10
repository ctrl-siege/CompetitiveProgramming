## Machine Problem 3

A gym wants to calculate the membership tier of each member based on their base score, months of membership, and number of days missed. Create a program that asks the user to enter their base score, months of membership, and days missed. The program will calculate the total score and determine the member's tier.

Formula: Total Score = Base Score + (Months of Membership * 5) - (Days Missed * 2)

The criteria for the membership tier will be the following:

- Gold: Total score is greater than or equal to 100.
- Silver: Total score is greater than or equal to 50 but less than 100.
- Bronze: Total score is below 50.

Input: The input consists of three integers, each provided on a separate line:

- The first line contains the base score.
- The second line contains the months of membership.
- The third line contains the number of days missed.

Output: Print the calculated total score on the first line and the membership tier on the second line.

Constraints:
- 0 ≤ Base Score ≤ 1000
- 0 ≤ Months of Membership ≤ 600
- 0 ≤ Days Missed ≤ 365
- Time Limit: 1 second
- Memory Limit: 256 MB

Sample Input:
```
85
4
5
```

Sample Output:
```
95
Silver
```