## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = {'a': 100, 'b': 200}
dict2 = {'b': 300, 'c': 400}

def merge():
    merged = {**dict1, **dict2}
    print("Merged dictionary:", merged)

merge()

```
## Output
![image](https://github.com/user-attachments/assets/3425f03e-b520-4b05-a52e-2b04b6a2cc04)

## Result
Program has been executed successfully.
