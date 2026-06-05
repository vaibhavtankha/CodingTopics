# Heaps 

## Java 
```java
PriorityQueue<Integer> minHeap = new PriorityQueue<>();
```

- default min heap 

- Max heap    
```java
PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>(Collections.reverseOrder());
```

##  Important Heap Operations
| Operation  | Complexity |
| ---------- | ---------- |
| Insert     | O(log n)   |
| Remove Top | O(log n)   |
| Peek       | O(1)       |
| Build Heap | O(n)       |


```java 
Commands for basic operation
pq.offer(10);  // add 
pq.poll() ; //remove
pq.peek() ; // look but dont remove from heap

```

- using comparator to sort :
