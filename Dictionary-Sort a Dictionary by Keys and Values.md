# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
Add Code here
```
# Step 2: Define the original dictionary
my_dict = {'banana': 'yellow', 'apple': 'red', 'cherry': 'dark red', 'blueberry': 'blue'}

# Step 3: Sort by keys alphabetically
sorted_by_keys = dict(sorted(my_dict.items()))

# Step 4: Sort by values alphabetically
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Step 5: Display the original and sorted dictionaries
print("Original Dictionary:")
print(my_dict)

print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)

print("\nDictionary Sorted by Values:")
print(sorted_by_values)
```
##output
```
Original Dictionary:
{'banana': 'yellow', 'apple': 'red', 'cherry': 'dark red', 'blueberry': 'blue'}

Dictionary Sorted by Keys:
{'apple': 'red', 'banana': 'yellow', 'blueberry': 'blue', 'cherry': 'dark red'}

Dictionary Sorted by Values:
{'blueberry': 'blue', 'cherry': 'dark red', 'apple': 'red', 'banana': 'yellow'}
```

## Result
The program successfully sorts the dictionary by both keys and values.
