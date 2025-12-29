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
file = open("C:/Users/acer/Downloads/heights.csv", "r")

count = 0


for line in file:
 
    if line.strip() and line[0] != 'T':
        count += 1


print("Number of lines not starting with 'T':", count)


file.close()
```

## Output
<img width="966" height="333" alt="Screenshot 2025-12-28 145700" src="https://github.com/user-attachments/assets/07cd76a6-f3fa-408c-897b-14a7aa1ffe5b" />

## Result
thus the python program is executed sucessfully!
