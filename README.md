## NAME: ANTONY YOUVAN YUVARAJA A
## REG NO: 212225060020
## List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
L=[153,147,124,102] 
print(sum(L)))
```
## Output
<img width="600" height="211" alt="image" src="https://github.com/user-attachments/assets/e9ba5355-0760-4a11-a329-b4d3e852c43f" />

## Result
Thus, the program has been successfully executed
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
```
import re
ls=[] 

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items: 
    if not re.search(r"e",i):
        ls.append(i)
print(ls)
```
## Output
<img width="437" height="167" alt="image" src="https://github.com/user-attachments/assets/57598bd0-2a5a-4321-a7b1-fa46c3d0ec55" />

## Result
Thus, the program has been successfully executed
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
s = input()

i = int(input())
if 0 <= i < len(s):
    result = s[:i] + s[i+1:]
    print(result)
else:
    print("Invalid index")
```

## Output
<img width="533" height="182" alt="image" src="https://github.com/user-attachments/assets/2c25f929-0f9c-4a81-9a8a-bba34c9686a8" />

## Result
Thus the program has been successfully executed
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
string="google"

if string==string[::-1]: 

    print ("The entered string is palindrome")
else:

    print ("The entered string is not palindrome")
```



## Output
<img width="691" height="162" alt="image" src="https://github.com/user-attachments/assets/c51ada46-f98c-4d1f-8a6b-c8cfc3a6b5d2" />

## Result
Thus, the program has been successfully executed.
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
Add code here
```

x=("s", 8, "a", "v", "n", "g", "u", "r", "c", "e") 

print("n" in x)
```

## Output
<img width="571" height="217" alt="image" src="https://github.com/user-attachments/assets/028b6960-8b39-4cfe-9ea4-dfd3463cf2dd" />

## Result
Thus, the program has been successfully executed
