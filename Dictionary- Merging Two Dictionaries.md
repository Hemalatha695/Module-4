## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
Add code here
```
# Step 1: Define two dictionaries
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

# Step 2: Define a function to merge two dictionaries
def merge(d1, d2):
    merged = {**d1, **d2}  # d2 values overwrite d1 if keys overlap
    return merged

# Step 3: Call the function and print the result
merged_dict = merge(dict1, dict2_
```
## Output
![image](https://github.com/user-attachments/assets/49767153-df28-4d0f-a3ef-047deeac491d)

## Result
The program correctly merges the dictionaries and handles key collisions as expected.
