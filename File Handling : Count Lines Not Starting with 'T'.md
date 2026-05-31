# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
file = open("story.txt", "r")

count = 0

for line in file:
    if not line.startswith('T'):
        count += 1

file.close()

print("Number of lines not starting with 'T':", count)
```
## Output
<img width="1288" height="173" alt="image" src="https://github.com/user-attachments/assets/afa4ee10-5ba8-43a9-9f9a-98e9f9a7764c" />

## Result
