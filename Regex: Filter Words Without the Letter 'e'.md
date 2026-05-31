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
# Regex in Python: Filter Words Without the Letter 'e'

import re

l1 = []

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)

## Output
<img width="433" height="330" alt="Screenshot 2026-05-31 110420" src="https://github.com/user-attachments/assets/895aa781-5658-401b-8737-7cd019e27bc9" />

## Result
Thus, the Python program using regular expressions to filter words that do not contain the letter 'e' was written and executed successfully.
