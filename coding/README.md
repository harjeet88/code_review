# Spark
1. Given an array with random 0s and 1s. Arrange all 0s to left and 1s to right.
input: [0, 0, 1, 1, 0, 1, 0]
Output: [0, 0, 0, 0, 1, 1, 1]
 
 
2. Given a table with students name, subject and their total marks, find the student with second highest mark in each subject.
A, maths, 90
B, maths, 100
B, physics, 85
C, maths, 92
A, physics, 75
C, physics, 92
 
C, maths, 92
B, physics, 85
 
3. Find frequency of word in each line

4. Given data

User	from_city	to_city
A	NA	Bangalore
B	NA	Delhi
B	Delhi	Bangalore
C	NA	Mumbai
C	Mumbai	Bangalore
C	Bangalore	Chennal
C	Chennai	Hyderabad
D	NA	Bangalore
D	Bangalore	Hyderabad
D	Hyderabad	Chennal
D	Chennai	Delhi
E	NA
E	NA	Bangalore
E	Bangalore	Chennai
E	Chennai	Delhi
E	Delhi	Hyderabad
E	Hyderabad	Mumbai
F	NA	Bangalore
F	Bangalore	Mumbai
F	Mumbai	Chennai
F	Chennai	Delhi
G	NA	Bangalore
G	Bangalore	Hyderabad

List of users who can fly from source: Bangalore  to destination: Hyderabad.

 
5. Sort the below list in order of quantity
Input = [['p0', 15], ['p1', 10], ['p2', 2],['p4', 150]]
 
Ans: https://www.geeksforgeeks.org/python-sort-list-according-second-element-sublist/

 
6. Return the diff: A-B
str1 = "1 2 3 4 5 6 7 8 9 10 10"
str2 = "1 2 3 4 5 11"
 
Output:
6 7 8 9 10 10 11
 

7.
Csv file like this: 
1st col: store id, rest are product ids
 
1,p1,p2,p3,p4
2,p1,p2
3,p1,p2,p3,p4,p5
4,p1,p2,p3,p4,p5,p5,p6
5,p1,p2,p3,p4,p5,p6,p7,p8
 
Store with the highest number of products

 
8.
1,dilip,1000, 01/01/2020 -> null
1,dilip,2000, 02/01/2020 - > Up
1,dilip,1000, 03/01/2020 -> down
1,dilip,2000, 04/01/2020 -> 
1,dilip,3000, 05/01/2020
1,dilip,1000, 06/01/2020 - 
 
Salary trend. (Same, up , down)
 
1. Two files: product file:
product_id,product_name,price
0,p0,22
1,p1,85
2,p2,109
 
Order file:
order_id,product_id,employee_id,date,qty_Sold
1,p0,0,2020-11-11,12
2,p0,0,2020-11-11,71
3,p0,0,2020-11-11,7
4,p1,0,2020-11-11,85
 
Total revenue = SUM (price * quantity sold)


