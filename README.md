# ProblemSolving
Problem Solving
Find the Least Frequently Occurring Digit in a series of numbers
Kamal is a data analyst in a lottery management organization.
One of the tasks assigned to Kamal is to find the least frequently occurring digit in a series of input numbers. Below are a couple of examples to illustrate how to find the Least Frequently Occurring Digit in a series of input numbers.
Example 1:
If the series of input numbers are [1236,262,666,121]
We notice that,
0 occurs 0 time
1 occurs 3 time
2 occurs 4 time
3 occurs 1 time
4 occurs 0 time
5 occurs 0 time
6 occurs 5 time
7 occurs 0 time
8 occurs 0 time
9 occurs 0 time
We observe that-
1 is the lowers frequency in this series and
3 is the digit that occur 1 time
Thus, the Least Frequently Occurring Digit in this series is 3.
NOTE1: As shown in above example, please not that the digits that do not occur at all(i.e. the digits that occur 0 time) should not be considered while finding the least frequently occurring digit.
NOTE2: If more than one digit occur the least frequent time, then the smallest of the digits should be chosen as the answer. See below example for clarity on this point
Example2:
If the series of input numbers is [1237, 202,666,140]
We notice that,
0 occurs 2 time
1 occurs 2 time
2 occurs 3 time
3 occurs 1 time
4 occurs 1 time
5 occurs 0 time
6 occurs 3 time
7 occurs 1 time
8 occurs 0 time
9 occurs 0 time
We observe that-
1 is the lowest frequency in this series and
3,4 and 7 are the digit that occur 1 time
The smallest of these three digits (3, 4 and 7) is 3. Thus, the Least Frequently Occurring Digit in this series is 3.
Kamal decides to write the logic in the below method for finding the Least Frequent Occurring Digit in the provided input series of numbers.
import java.util.ArrayList;
