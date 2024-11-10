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

![Screenshot 2024-11-10 210819](https://github.com/user-attachments/assets/5d763e7d-f4cf-4720-938f-f8b2eece7f61)


ii) while…do:

![Screenshot 2024-11-10 210909](https://github.com/user-attachments/assets/e924413d-b230-49cc-8ed1-f5e6898db48c)


iii) switch:

![Screenshot 2024-11-10 211155](https://github.com/user-attachments/assets/e0546f04-3c6a-49d2-8eae-249f7893d1b5)


iv) if else:

![371402489-5f2a81b0-c188-4423-8a50-6c9b654aeac3](https://github.com/user-attachments/assets/5650ab1a-571c-42da-b517-6f735130656f)

v) for:

![371403549-acb1e794-570d-47a7-8681-42acbbeff8ab](https://github.com/user-attachments/assets/7a092dfb-d562-425c-b078-2150acb54647)




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


