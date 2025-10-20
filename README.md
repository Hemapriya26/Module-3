DATE : 16.10.2025
---

# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the *sum of all elements* in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in sum() function to calculate the total.
3. Print the result.

## 🧾 Program

```
def createlist(n):
    l=[]
    for i in range(2,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```

## Output
![444868357-707d0836-85eb-4ab5-802b-5bc9a6521f8f](https://github.com/user-attachments/assets/fa81b263-752d-443f-9280-77481df2e42b)


## Result
Thus the program executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter 'e'*, using **regular expressions (regex)*.

## 🧠 Algorithm
1. Import the re module.
2. Initialize an empty list l1 to store results.
3. Define a list of words:  
   items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
4. Iterate through each word in the list:
   - Use re.search(r"e", i) to check if the word contains 'e'.
   - If *not*, append the word to l1.
5. Print the final filtered list.

## 🧾 Program

```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```

## Output
![WhatsApp Image 2025-05-13 at 21 50 28_43489c13](https://github.com/user-attachments/assets/26e676d1-dd52-427d-b2ad-6d6dcaefec63)

## Result
Thus the given program is executed successfully.

# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named remove that takes the input string as an argument.
2. Read the index n from the user input.
3. Initialize an empty string a to store the new string.
4. Iterate over each index of the string using a for loop.
5. Check if the current index i is not equal to n.
6. If i != n, append the character at index i to string a.
7. After the loop, return the modified string a.
8. Print the final result.

## 💻 Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```
## Output
![WhatsApp Image 2025-05-13 at 21 50 47_8d65365a](https://github.com/user-attachments/assets/1f4c3dd4-fe4e-48a7-af2c-8179a1233ced)

## Result
Thus the given program is executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string "google" is a *palindrome* or not, without using built-in palindrome checking functions.


## 🧠 Algorithm
1. Assign the string "google" to a variable.
2. Reverse the string manually using slicing ([::-1]).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.
   

## 🧾 Program

```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
![WhatsApp Image 2025-05-13 at 21 51 05_5b19a368](https://github.com/user-attachments/assets/b0d779bb-04bf-496e-8ac4-e1db48af370d)

## Result
Thus the given program is executed successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple x with some letters and numbers.
2. Use the in operator to check if the string 'n' exists within the tuple.
3. Use the in operator to check if the integer 8 exists within the tuple.
4. Print the results.

## 🧾 Program

```
tuplex=eval(input())
print("n" in tuplex)
print("8" in tuplex)
```

## Output
![WhatsApp Image 2025-05-13 at 21 51 57_3a8d51d2](https://github.com/user-attachments/assets/5faa816e-f434-46f1-9053-b539d559874a)

## Result
Thus the given program is executed successfully.
