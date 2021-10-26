# Linked Lists and Big Oh

## Big Oh notation

- way to measure rate of growth/complexity
- measures the efficiency of an algorithm
  - mostly concerned with time
  - but also resources (i.e. memory)

- three measurements of time:
  1. milliseconds from start of execution to end
  2. number of operations
  3. number of basic operations

## orders of growth

- describes the rate of time/space complexity
- alogorithmic growth
- logarithmic growth

## Linked Lists and how to do them in javascript

- there is no linked list in JS so we must jerryrig our own method

- linkedl ists are recursive
- consists of nodes, each node is a data reference, as well as a reference to another node
- points to specific things in an orderly way
- method of linking data together *dynamically*
  - other languages have arrays but they aren't dynamic (type and length must be declared upfront)
  - linked lists grow as needed
  - often used to move items from one array to another

## terminology

- Node: what makes up a linked list (contains a value and a next property)
- Value: anything that is stored in a linked list
- Next: a reference to another node
- Current: A node that is being read during a traversal
- Head: the first node in a linked list
- Singly: all nodes have only one reference to another node
- Doubly: all nodes have two references to other nodes
  - Previous: reference to a node other than next

## traversal

Reading the contents of an "iterable" (ie a thing made up of repeating pieces)

```javascript example

class Node {
  constructor(value) {
    this.value = value;
    this.next = null
  }
}

class LinkedList {
  constructor(value) {
    this.head = null
  }
}

const list = new LinkedList();

list.head = new Node(10);
list.head.next = new Node(25);
list.head.next.next = new Node(22);
list.head.next.next.next = new Node(13);

console.log(list);

const traverseIterative = (head) => {
  console.log(head);

  let current = head;

  console.log(head.next)

  while (current) {
    current = current.next
  }
}
traverseIterative(list.head);

let traverseRecursion = (current) => {

  if (current) {
  console.log(current)
  traverseRecursion(current.next)
  } else {
    console.log('hard as puck boy')
  }
}
```
