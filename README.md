# Steiner-Tree-Algorithms
Algorithms implementing the Steiner Tree Problem


---

### Graph definition

We specif the number of nodes and edges and pick the terminals randomly.

```
Node: str
Graph: {Node: set(Node)} aka adjacency list
Terminals: set(Node)
Edge: frozenset([Node, Node])
Tree: set(Edge) aka edge list, used for steiner solution
Path: [Node]
ShortestPath: {(Node, Node): Path}
```

---

#### Steinlib - Library of functions for the Steiner tree problem

[link](http://steinlib.zib.de/steinlib.php)

- SteinerNet - [link](https://github.com/krashkov/SteinerNet)


---
#### Resources

- Graph visualization library - [link](https://pypi.org/project/graphviz/)
- Exact algorithm - [link](https://github.com/kellerb/steiner-tree-python)
- Dijkstra steiner ALgo in cpp - [link](https://github.com/Zakuta/dijkstra-steiner-algo)
- Approximation Algorithm - [link](https://github.com/mouton5000/DSTAlgoEvaluation)
- Parameterized Algorithm - [link](https://github.com/maoxc/steiner-tree-pas)

---

#### Heuristics

- https://github.com/atul2938/Steiner-Tree
- https://github.com/srmocher/Node-Weighted-Steiner-Problem