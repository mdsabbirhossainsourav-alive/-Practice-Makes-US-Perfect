Most programmers will tell you that one of the ways to improve your performance in competitive programming is to practice a lot of problems.

Our Chef took the above advice very seriously and decided to set a target for himself.

Chef decides to solve at least 10 problems every week for 4 weeks.

Given the number of problems he actually solved in each week over 

4 weeks as P1,P2,P3 and P4,output the number of weeks in which Chef met his target.

### Input Format
There is a single line of input, with 4 integers P1,P2,P3 and P4.These are the number of problems solved by Chef in each of the 4 weeks.
### Output Format
Output a single integer in a single line - the number of weeks in which Chef solved at least 10 problems.
### Constraints
1≤P,P2,P3,P4 ≤100
### Input
12 15 8 10
### Output
3

Chef solved at least 10 problems in the first, second and fourth weeks. 

He failed to solve at least 10 problems in the third week. 

Hence, the number of weeks in which Chef met his target is 3.

### Input
2 3 1 10
### Output
1

Chef solved at least 10 problems in the fourth week. He failed to solve at least 10 problems in all the other three weeks.

Hence, the number of weeks in which Chef met his target is 1.

### Input	
12 100 99 11
### Output
4

Chef solved at least 10 problems in all the four weeks. Hence, the number of weeks in which Chef met his target is 4.

### Input
1 1 1 1
### Output
0

Chef was not able to solve at least 10 problems in any of the four weeks. 

Hence, the number of weeks in which Chef met his target is 0.
