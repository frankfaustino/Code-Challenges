# Breadth First Search

Write a function that accepts a tree data structure and a value to search for.

Search for the value using a breadth-first search algorithm.

#### Reference
https://en.wikipedia.org/wiki/Breadth-first_search

#### Example:

```js
const tree = {
  x: 1,
  y: 1,
  z: {
    x: 1,
    y: 1,
    z: 1,
  },
  a: 2,
}

breadthFirstSearch(tree, 2) // will return true before it recursively searches `z`
```