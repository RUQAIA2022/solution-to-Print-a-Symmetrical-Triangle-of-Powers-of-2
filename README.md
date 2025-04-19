# solution-to-Print-a-Symmetrical-Triangle-of-Powers-of-2
from the problem statement we know:
-print a triangle where the numbers go up as powers of 2, and then come back down in reverse.
-An integer height which represents the number of rows in the triangle
the steps to do that :
1.Read input value height (number of rows)
2.Repeat the following steps for each row (from 0 up to the number entered):
3.Create a list called row that contains powers of 2 from 2^0 to 2^i.
4.Make a reversed copy of that list, but skip the last number (so the middle number doesn’t repeat).
5.Join the original list and the reversed list together into one full row.
6.Convert all the numbers to strings and join the numbers with spaces between them.
7.Ask the user to enter the number of rows they want in the triangle.
8.Print the row
