# Trees

## what is a tree?

a data structure made up of nodes

- non-linear 

- non-cyclical

- directional order

## terminology

- branch/edge: connection to another node
  - child: the descendant of a node

- leaf: a node which has no children/edges

- height: the number of edges from the root to the furthest leaf
  - number of *edges* NOT nodes!

- root: the first node in a tree

- recursive: every node will share the same properties
  - except for how many children a node might have
  - k: the max number of nodes a tree can have (for k-ary trees as opposed to binary trees)
  
- binary tree nodes have a left and right properties

1. Depth first: prioritizes travelling down left or right subnodes before looking at other nodes on current level

- Pre-order: start reading the current node's value before moving to the left, then to the right
  - root/current -> left -> right

``` javascript

function preOrder(current) { 

  console.log(current.value);

  if (current.left) {
    preOrder(current.left)
  }
  
  if (current.right) {
    preOrder(current.right)
  }
}

```

- In order: left -> root/current -> right
- Post order: left -> right -> root/current

2. Breadth first: finds all nodes on current level before traveling down to the next one
