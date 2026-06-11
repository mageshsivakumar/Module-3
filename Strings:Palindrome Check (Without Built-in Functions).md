# Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
       print(a[i],end='')
```
## Output
<img width="634" height="189" alt="544820783-9dd5c2f5-6ca3-405e-86f5-ecb42bc9be59" src="https://github.com/user-attachments/assets/22f441cd-7f19-4a63-93e2-8e3c14d0bc16" />

## Result
Thus the program executed successfully.
