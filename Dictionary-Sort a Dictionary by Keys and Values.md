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
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}
sorted_by_keys = dict(sorted(data.items()))
print("Sorted by keys:", sorted_by_keys)
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))
print("Sorted by values:", sorted_by_values)



## Sample Output
<img width="1332" height="370" alt="image" src="https://github.com/user-attachments/assets/3efa89ee-ab96-4f45-914a-7649228244f4" />


## Result
A Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order
  is excuted sucessful.


