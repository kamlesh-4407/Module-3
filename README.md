# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```python
list=eval(input())
total=sum(list)
print(total)
```
## Output

![image](https://github.com/user-attachments/assets/f207c463-a633-490d-8e5a-4059671d507c)

## Result
Thus,the program has been executed successfully.


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
```python
import re
l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      l1.append(i)
print(l1)
```
## Output

![image](https://github.com/user-attachments/assets/81efb6ee-4030-4118-8559-da2feb1cef69)

## Result
Thus,the program has been executed successfully.




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
```python
def remove(str): 
l=len(str) 
a="" 
n=int(input()) 
for i in range(0,l): 
if i==n: 
a=a+"" 
else: 
a=a+str[i] 
print(a)
```

## Output

![image](https://github.com/user-attachments/assets/9b40da2a-ea2c-4be9-b5d4-6fbbcfb23442)

## Result
Thus ,the program has been executed successfully.



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
```python
n=input()
m=n
a=n[::-1]
if(m==a):
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

![image](https://github.com/user-attachments/assets/af44721f-43cd-411c-8692-6c6be0801175)

## Result
Thus,the program has been executed successfully.



# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x=eval(input())
print("n" in x) 
print(8 in x)
```

## Output

![image](https://github.com/user-attachments/assets/3e58165a-ca58-4bb6-947c-f64d1d33dd3c)

## Result
Thus,the program has been executed successfully.

