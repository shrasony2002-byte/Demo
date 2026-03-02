#rules for identifiers and data types 
print("shraddha")
print(35)
print(45)
print(35+45)
name="shraddha"
print(type (name))
age =23 
print (type(age))
price =99.9
print(type(price))
age=23
old =False
a=None
print(type(old))
print(type(a))
a=15
b=25
diff= a-b
print(diff)
#expression excuetion
#string and string can operate and it is called concatenation
A,B ="2",3
txt ="@"
print((A+txt)*B)
#string and numeric value can not operate together
A,B =2,3
txt="@"
print(2*txt*3)

#numeric values can operate with all arithematic operators
A,B =2,3
C=4
print(A+B*C)

#arithematic expressions with intergers and float will result in float 
A,B = 10,5.0
C=A*B
print(C)

#integer division with float and int will result in displayed as float 
A,B = 1.5 ,3
C=A//B
print(C, A/B)

#EXPRESSION EXCUETION
#floor gives closets, integer which is lesser than or equal to the float value results of (A//B) is same as floor(A/B)
A,B=12,5
C=A//B
print(C)

A,B=12,-5
C=A//B
print(C)

#reminder is negative when denominator is negative
A,B= -5,2
C=A%B
print(C)

A,B= 5,2
C=A%B
print(C)

A,B= 5,-2
C=A%B
print(C)

""" CHAPTER 2 COMMENTS IN PYTHON
Using comments will help you to understanding and readability increases
"""
#print("hello") it wont be printed
print("world")# it was printed
#input in python input() statement is used to accept values (using keyboard) from user
name=input("name:")#string input
print(name)
age=int(input("age:"))#int input
print(age)
price=float(input("price"))# float input
print(price)
print("my name is", name,"and my age is", age ,"years old")

#python is indentation langauge
#conditional statements 
light =input("light")#if (condition):
if(light=="red"):
    print("stop")
elif(light=="yellow"):
    print("look")
elif(light=="green"):
    print("go")
else:
    print("light is broken")




