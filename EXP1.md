Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for
DATE: 13/03/25
REGISTER NUMBER : 212222040050
AIM:
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases

Algorithm:
Start the program.
Create separate files for each given program.
Write simple program for each construct.
the program with possible test cases.
Stop the program.
Program:
Do While:
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
While Do:
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
Switch:
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()
If Else:
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
For:
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate() 
Output:
Do While:
stl- EX 1 a

While Do:
stl- EX 1 b

Switch:
stl- EX 1 c

If Else:
stl- EX 1 d

For:
stl- EX 1 e

Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
