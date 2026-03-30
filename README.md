# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

L=[153,147,124,102] 
 
print(sum(L)))

## Output

<img width="514" height="192" alt="image" src="https://github.com/user-attachments/assets/c975acce-d61d-451e-a778-b72da1ce076b" />

## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

import re
l1=[] 

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items: 

   if not re.search(r"e",i): 
      l1.append(i) 

print(l1)

## Output

<img width="367" height="133" alt="image" src="https://github.com/user-attachments/assets/8b9305cb-c8fa-4e9d-8f76-b73508404b98" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)

```
## Output

<img width="640" height="130" alt="image" src="https://github.com/user-attachments/assets/2b09655a-beef-4412-86b6-416b67e588fd" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.


# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```

if string==string[::-1]: 

   print ("The entered string is palindrome")

else: 

   print ("The entered string is not palindrome") 

```
## Output

<img width="496" height="107" alt="image" src="https://github.com/user-attachments/assets/05f00a7c-ecc4-401e-8f4b-2fd603ff0cba" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.
