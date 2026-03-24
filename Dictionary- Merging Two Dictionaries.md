# PYTHON MODULE - 4
# (B) Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim:
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm:
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program:

    def merge(dict1,dict2):
        merged_dict = {**dict1 , **dict2}
        print(merged_dict)
    dict1 = eval(input("Dictionary-1 : "))
    dict2 = eval(input("Dictionary-2 : "))
    merge(dict1,dict2)

## Output:

<img width="478" height="221" alt="image" src="https://github.com/user-attachments/assets/fa7aa3b4-ec3b-4b8e-9344-d439961f25d2" />



## Result:

Thus, The Python program that merges **two dictionaries**
