# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE:  01.10.2024                                                                          
### REGISTER NUMBER : 212222040091
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:

```
def Palindrome(string):
    for i in range(0, int(len(string)/2)): 
        if(string[i] != string[len(string)-i-1]): 
            return False 
    return True 

s = input("Enter a string: ") 

c = 1 
for i in s: 
    if not(i.isalpha()): 
        c = 0 
        break # Added to stop checking once an invalid character is found

if(c == 0): 
    print("Enter a valid string") 
else:
    answer = Palindrome(s)
    if(answer == True): 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome")
```

### Output:

![Screenshot 2024-10-28 203304](https://github.com/user-attachments/assets/28ca9697-a1c8-47ed-a986-488964791145)

![Screenshot 2024-10-28 203317](https://github.com/user-attachments/assets/025bfbe3-16ed-4cad-b396-06520e877dfc)


### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.