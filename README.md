#if-elif-else-problems 
#1.even or odd
integer=int(input("enter a number: "))

if integer%2==0:
    print("input number is even")
    
else:
    print("input number is odd")

#2.positive or negative

number=int(input("enter a number: "))
if number>0:
    print("entered number is positive")
    
elif number<0:
    print("entered number is negative")
    
else:
    print("entered number is zero")

3# voting eligibility
age=int(input("enter your age: "))
if age>=18:
    print("This person eligible to vote")
    
else:
    print("this person is not eligible to vote")

#4 largest of two number
num1=int(input("enter a number: "))
num2=int(input("enter a number: "))
if num1>num2:
    print("num1 is greater than num2")
elif num2>num1:
    print("num2 is greater than num1")
else:
    print("both numbers are equal")
    
#4
age=int(input("enter age: "))
if age>=80:
    print(" super senior")
elif age<80 and age>=60:
    print("senior")
elif age<60 and age>=24:
    print(" Working professionals")
elif age<24 and age>=10:
    print("student")
else:
    print("children")
    
