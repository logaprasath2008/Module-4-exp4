# (D) Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim:
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm:
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program:

    lst = [1,4,8,9,10,5]
    try :
        index = int(input("Enter a index : "))
        print("Th Element in the given index is ",lst[index])
    except :
        print("You're out of list range")

## Output:

<img width="470" height="221" alt="image" src="https://github.com/user-attachments/assets/7ff5add7-5a17-44c3-a781-3b2e85708884" />
<img width="480" height="241" alt="image" src="https://github.com/user-attachments/assets/05ba01ed-bfc6-4198-896a-0f33919c5440" />


## Result:

Thus, The Python program that handles an **IndexError** when trying to access an element beyond the available range of a list was executed successfully.
