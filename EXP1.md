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
![image](https://github.com/user-attachments/assets/08c4e7c3-ea1f-4549-ad53-3197463ffb1f)



While Do:
![image](https://github.com/user-attachments/assets/123d7ad7-cd6a-427b-9af7-028d469b27c9)


Switch:
![image](https://github.com/user-attachments/assets/b9e65971-1d8c-48f6-9eaf-38955fd54e12)


If Else:
![image](https://github.com/user-attachments/assets/fb4f9594-ef11-445b-9c37-7144cc3362b3)


For:
![image](https://github.com/user-attachments/assets/c97d6b6d-ad84-4880-80eb-a244acc570a1)


Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
