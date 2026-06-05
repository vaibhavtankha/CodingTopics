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
``` java

public class Employee {
    private String name;
    private int empId;
    private String city;

    public Employee(String name, int empId, String city) {
        this.name = name;
        this.empId = empId;
        this.city = city;
    }

    public String getName() {
        return name;
    }

    public int getEmpId() {
        return empId;
    }

    public String getCity() {
        return city;
    }

    @Override
    public String toString() {
        return "Employee{name='" + name + "', empId=" + empId +
                ", city='" + city + "'}";
    }
}   



PriorityQueue<Employee> heap =
        new PriorityQueue<>(Comparator.comparing(Employee::getName));   

heap.offer(new Employee("John", 101, "Seattle"));  
heap.offer(new Employee("Alice", 102, "Boston"));  
heap.offer(new Employee("David", 103, "Chicago"));  
heap.offer(new Employee("Bob", 104, "Austin"));  

while (!heap.isEmpty()) {  
    System.out.println(heap.poll());  
}


PriorityQueue<Employee> heap =
    new PriorityQueue<>(
        Comparator.comparing(Employee::getName)
                  .thenComparing(Employee::getEmpId)
    );


PriorityQueue<Employee> heap =
    new PriorityQueue<>(
        Comparator.comparing(Employee::getName,
                             String.CASE_INSENSITIVE_ORDER)
    );    
```
