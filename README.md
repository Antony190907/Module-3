## NAME: ANTONY YOUVAN YUVARAJA A
## REG NO: 212225060020
## List Operations in Python: Sum of List Items
🎯 Aim

To write a Python program that calculates the sum of all elements in a list.

🧠 Algorithm

Define a list of numbers.
Use Python’s built-in sum() function to calculate the total.
Print the result.

🧾 Program
```
list1=[1, 2, -8]
total=sum(list1)
print(total)
```
Output:

<img width="335" height="164" alt="WhatsApp Image 2026-06-01 at 9 27 36 AM" src="https://github.com/user-attachments/assets/af4cb250-470c-4e4f-8b90-bb9d7d4ea2e0" />

Result:

Thus to write a Python program that calculates the sum of all elements in a list is done successfully.

## Regex in Python: Filter Words Without the Letter 'e'

🎯 Aim

To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

🧠 Algorithm

Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.

🧾 Program

```
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

result = [word for word in items if 'e' not in word]
print(result)
```

Output:

<img width="592" height="173" alt="image" src="https://github.com/user-attachments/assets/c644ccba-89f5-40bb-9cf3-ee35928639dd" />

Result:

Thus to write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is done successfully.

## 🧹 Strings-Remove Nth Index Character from a String

🎯 Aim

To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm

Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.

💻 Program

```
def remove(s):
    n = int(input())
    c=s[:n] + s[n+1:] 
    print(c)
```

Output:

<img width="656" height="206" alt="WhatsApp Image 2026-06-01 at 9 34 54 AM" src="https://github.com/user-attachments/assets/98125369-db8a-4d1a-88fb-64a50ef88aaf" />

Result:

Thus to write a Python program that accepts a string and removes the character at a specified index is done successfully.


## Strings-Palindrome Check in Python (Without Built-in Functions)

🎯 Aim

To write a Python program to check whether the string "malayalam" is a palindrome or not, without using built-in palindrome checking functions.

🧠 Algorithm

Assign the string "google" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.

🧾 Program

```
text = input()

rev = text[::-1]

if text == rev:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

Output:

<img width="902" height="238" alt="WhatsApp Image 2026-06-01 at 9 43 50 AM" src="https://github.com/user-attachments/assets/84f29fcd-5773-47c3-80ec-15c2cc267675" />

Result:

Thus to write a Python program to check whether the string "malayalam" is a palindrome or not, without using built-in palindrome checking functions is done successfully.

## Tuple in Python: Check Element Existence

🎯 Aim

To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

🧠 Algorithm

Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 8 exists within the tuple.
Print the results.

🧾 Program

```
tuplex = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print( 8 in tuplex)
```

Output:

<img width="484" height="212" alt="image" src="https://github.com/user-attachments/assets/9e2cff63-c8a2-4193-9060-461c1f4eef13" />


Result:

Thus to write a Python program that checks if the element 'n' and the element 8 exist within a given tuple is done successfully.




