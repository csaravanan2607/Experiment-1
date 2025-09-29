# Experiment - 1
##  Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c)if …else d) switch e) for

## a) Aim :
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm :
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program :

## a) do while
~~~
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

~~~
## Output :
<img width="697" height="113" alt="image" src="https://github.com/user-attachments/assets/b8b8f1e7-063f-484d-8e5f-edf6a268fad7" />


## b) while do
~~~
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
~~~
## Output :
<img width="637" height="113" alt="image" src="https://github.com/user-attachments/assets/fb8e6217-7e57-45ef-9296-e01a806682bd" />

## c) if else
~~~
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
~~~
## Output :
<img width="671" height="87" alt="image" src="https://github.com/user-attachments/assets/aeb7d0a1-2458-4e30-94cc-aadb3a3c8630" />

## d) switch
~~~
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
~~~
## Output :
<img width="672" height="130" alt="image" src="https://github.com/user-attachments/assets/116895ff-48a1-4651-9f0b-9d8eecd16a65" />

## e) for
~~~
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
~~~
## Output :
<img width="719" height="72" alt="image" src="https://github.com/user-attachments/assets/0cd32713-afe7-4572-aa33-69c81413402f" />

## Result :
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


