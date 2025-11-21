# 🔄 Types of Queue-Circular Queue in Python

This project demonstrates the implementation of a **Circular Queue** in Python. The queue accepts 3 user values, performs enqueue and dequeue operations, and displays the removed values.

---

## 🎯 Aim

To develop a Python program that implements a Circular Queue:
- Accepts 3 values from the user
- Removes the 3 values from the queue
- Displays the removed values

---

## 🧠 Algorithm

1. **Initialize** a circular queue of fixed size (e.g., 5).
2. **Define the following functions**:
   - `enqueue()`: Inserts an element into the queue.
   - `dequeue()`: Removes an element from the queue.
   - `display()`: Shows the queue contents.
3. Accept 3 values from the user using the `enqueue()` method.
4. Remove 3 values using the `dequeue()` method.
5. Print the removed values.

---

## 💻 Program:
```class MyCircularQueue():
    def __init__(self, k):
        self.k = k
        self.queue = [None] * k
        self.head = self.tail = -1
    def enqueue(self, data):
        if self.head==-1:
            self.head=0
            self.tail=0
            self.queue[self.head]=data
        else:
            self.head=(self.head+1)%self.k
            self.queue[self.head]=data
    def printCQueue(self):
        i=self.tail
        while(True):
            print(self.queue[i],end=' ')
            if i==self.head:
                break
            i=(i+1)%self.k
       
obj = MyCircularQueue(5)
n=int(input())
for i in range(n):
    obj.enqueue(input())
obj.printCQueue()
```

### Output:

<img width="1067" height="476" alt="image" src="https://github.com/user-attachments/assets/cdbd03b3-d735-4792-b30a-83bed469067a" />

## Result:
Thus to develop a Python program that implements a Circular Queue to remove the 3 values from the queue is created and executed successfully.
