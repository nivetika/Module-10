# # Stack-Stack Reversal Program 🔁

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```from queue import LifoQueue
n=int(input())
stack=LifoQueue(maxsize=5)
for i in range(n):
    v=int(input())
    stack.put(v)
print(stack.full())
while not stack.empty():
    print(stack.get())
```

## 🧪 Sample Input and Output

<img width="1004" height="452" alt="image" src="https://github.com/user-attachments/assets/51231c29-fa8f-4334-8f5e-1dd4dae6dfc5" />

## Result
Thus to write a Python program that reverses the values in a stack using standard stack operations is created and executed successfully..
