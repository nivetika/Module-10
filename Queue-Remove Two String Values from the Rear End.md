# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
```
from collections import deque
n=int(input())
lst=deque()
for i in range(n):
    lst.append(input())
for i in range(2):
    lst.popleft()
print(list(lst))
```

### Output:

<img width="1048" height="500" alt="image" src="https://github.com/user-attachments/assets/f23990e6-a038-4fd7-aefb-b7e3fbe24fa3" />

## Result:
Thus to write a python program to remove the last two values from the rear end of the list is created and executed successfully.
