# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 24.9.24                                                                      
### REGISTER NUMBER : 212222040091

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

i)do…while:

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

ii) while…do:

```
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
```

iii) switch:

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 
```
iv) if else:

```
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
        print(“Enter a valid number.”) 
```

v.) for:

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 

```

### Output:

i)do…while:

![Screenshot 2024-10-01 135840](https://github.com/user-attachments/assets/ccedd5c9-0a59-4772-af73-5c7bd4cbabe9)


ii) while…do:

![Screenshot 2024-10-01 141338](https://github.com/user-attachments/assets/49775edc-bcde-4795-bbbb-6ccd8fd0772e)


iii) switch:

![Screenshot 2024-10-01 143652](https://github.com/user-attachments/assets/c1453484-1fe6-4e27-9321-2d4cd4caafb9)


iv) if else:

![Screenshot 2024-10-08 142941](https://github.com/user-attachments/assets/ec0017de-4c31-4dbd-97b1-cdc5553684b2)

v) for:

![Screenshot 2024-10-08 143731](https://github.com/user-attachments/assets/37aeca4a-0b5d-43c7-b638-a961ad2995c5)




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


