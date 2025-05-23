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
```python
def remove(string, n):
    return string[:n] + string[n+1:]  # Concatenating parts before and after n

string = input("Enter a string: ")
n = int(input("Enter index to remove: "))

if 0 <= n < len(string):
    result = remove(string, n)
    print("Modified string:", result)
else:
    print("Invalid index! Please enter a valid index.")
```

## Output
![image](https://github.com/user-attachments/assets/0063777c-30d3-415a-9c58-8b145adec9cc)

## Result
Thus, the output is verified successfully
