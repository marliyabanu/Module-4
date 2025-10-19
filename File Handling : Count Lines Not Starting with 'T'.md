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
with open("story.txt", "r") as file:
    # Step 2: Initialize the counter
    count = 0
    for line in file:
        # Strip leading whitespace and check first character
        if line.strip() and line.strip()[0] != 'T':
            count += 1
print("Number of lines that do not start with 'T':", count)



## Output
<img width="1787" height="422" alt="image" src="https://github.com/user-attachments/assets/9c3a8353-9136-4dcd-b1ae-40b70c716142" />


## Result
A Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` is excuted sucessful.

