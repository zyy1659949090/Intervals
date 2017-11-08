# Intervals

Intervals

Description

There is given the series of n closed intervals [ai; bi], where i=1,2,...,n. The sum of those intervals may be represented as a sum of closed pairwise non−intersecting intervals. The task is to find such representation with the minimal number of intervals. The intervals of this representation should be written in the output file in acceding order. We say that the intervals [a; b] and [c; d] are in ascending order if, and only if a <= b < c <= d.

Task

Write a program which:
reads from the std input the description of the series of intervals,
computes pairwise non−intersecting intervals satisfying the conditions given above,
writes the computed intervals in ascending order into std output

Input

In the first line of input there is one integer n, 3 <= n <= 50000. This is the number of intervals. In the (i+1)−st line, 1 <= i <= n, there is a description of the interval [ai; bi] in the form of two integers ai and bi separated by a single space, which are respectively the beginning and the end of the interval,1 <= ai <= bi <= 1000000.

Output
The output should contain descriptions of all computed pairwise non−intersecting intervals. In each line should be written a description of one interval. It should be composed of two integers, separated by a single space, the beginning and the end of the interval respectively. The intervals should be written into the output in ascending order.

Sample Input

5

5 6

1 4

10 10

6 9

8 10

Sample Output

1 4

5 10
