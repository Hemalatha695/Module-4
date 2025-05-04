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
Add code here
```
# Step 1: Open the file in read mode
try:
    with open('story.txt', 'r') as file:
        count = 0  # Step 2: Initialize counter

        # Step 3: Iterate through each line
        for line in file:
            # Strip leading whitespace and check if line doesn't start with 'T'
            if not line.lstrip().startswith('T'):
                count += 1

    # Step 4: Print the result
    print("Number of lines that do not start with 'T':", count)

except FileNotFoundError:
    print("The file 'story.txt' was not found.")
```

## Output
```
Number of lines that do not start with 'T': 3
```
## Result
the program reads the file safely, trims leading spaces to handle indentation, and correctly counts lines that don't start with 'T'
