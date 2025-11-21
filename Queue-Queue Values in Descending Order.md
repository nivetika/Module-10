# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 

```
from collections import deque
q=deque()
for i in range(5):
    q.append(input())
newq=deque(sorted(q,reverse=True))
print(*list(newq))
```
### Output:

<img width="1023" height="446" alt="image" src="https://github.com/user-attachments/assets/836f8e76-0eed-41f7-ab72-d369fe8a6c04" />

## Result:
Thus to create python program to display the queue in descending order is created and successfully.
