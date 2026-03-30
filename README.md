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

