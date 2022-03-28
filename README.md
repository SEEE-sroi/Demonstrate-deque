# Demonstrate-deque and deque provides an 0(1) time complexity for append and pop opeartions compared to list which probides 0(n) time complexity
importing deque from collections
from collections import deque
queue = deque (['name','age','DOB'])
print(queue)
