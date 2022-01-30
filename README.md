# Python-Practice
#[1]
##Making Numerical Lists##
#Using the range() function:

for value in range(1,11):
    print(value)

#output:
1
2
3
4
5
6
7
8
9
10

#Python to start counting at the first value you give it, and it stops when it reaches the second value you provide.
#Because it stops at that second value, the output never contains the end value, which would have been 11 in this case.
#To print the numbers from 1 to 11, you would use range(1,12)

#[2]
####Using range() to Make a List of Numbers:

even_number=list(range(2,21,2))
print(even_number)
#output:[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]


#[3]
#You can create almost any set of numbers you want to using the range() function.
#For example, consider how you might make a list of the first 10
#square numbers (that is, the square of each integer from 1 through 10).
#In Python, two asterisks (**) represent exponents. 
#Here’s how you might put the first 10 square numbers into a list:

squares=[]
for i in range(1,11):
    square=i**2
    squares.append(object)
print(squares)
#output:[1, 4, 9, 16, 25, 36, 49, 64, 81, 100](check yourself)
