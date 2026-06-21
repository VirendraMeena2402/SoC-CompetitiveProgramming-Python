# Summer of Code – Competitive Programming with Python (Project 32)

Midterm checkpoint submission containing all assignments completed so far, along with the Google Colab links and topics covered each week.

## Assignments

| Week | Topic Focus | Colab Link |
|------|-------------|------------|
| Week 1 | Python Basics & Input Handling | [Open in Colab](PASTE_WEEK_1_LINK_HERE) |
| Week 2 | Data Structures (Dict, Set, List, Tuple) | [Open in Colab](PASTE_WEEK_2_LINK_HERE) |
| Week 3 | Searching, Sorting & Recursion | [Open in Colab](PASTE_WEEK_3_LINK_HERE) |
| Week 4 | Graph Algorithms | [Open in Colab](PASTE_WEEK_4_LINK_HERE) |

---

## Topics Learnt

### Week 1 – Python Foundations
- Taking and parsing input (`input()`, `split()`, `map()`)
- Basic arithmetic operations (sum, product)
- String traversal and character counting (vowel counting)
- Character arithmetic using `ord()` / `chr()` (alphabet shifting with wraparound)
- Loops with sentinel-based termination (`while True` + `break`)
- Conditional filtering with modulo operations (divisibility rules, XOR-style conditions)
- Digit sum reduction using iterative loops

### Week 2 – Data Structures in Python
- Dictionaries for structured record-keeping (student records, inventory, course data)
- Nested dictionaries and dictionary comprehensions
- Sets for uniqueness and relationship modeling (mutual friends, social network analysis)
- `collections.Counter` for frequency analysis (word frequency in text)
- `collections.defaultdict` for graph-like and grouped data
- Sorting complex objects with custom keys (`sorted()` with `key=lambda`)
- Tuples for fixed-size grouped return values
- Building small systems: grade management, inventory management, course scheduling, recommendation systems, tournament ranking, and traffic network analysis
- Introduction to graph-like representations and `heapq` for route optimization

### Week 3 – Searching, Sorting & Recursion
- Linear Search
- Recursive Binary Search
- Recursion fundamentals (factorial)
- Insertion Sort (implemented from scratch)
- Merge Sort (divide-and-conquer recursion)
- Two-pointer technique (counting pairs with a given sum in a sorted array)

### Week 4 – Graph Algorithms
- Graph representation using adjacency lists (`defaultdict(list)`)
- Breadth-First Search (BFS) and Depth-First Search (DFS) traversal
- Cycle detection in undirected graphs using DFS
- Topological Sort using Kahn's Algorithm (BFS-based, in-degree tracking)
- Dijkstra's Algorithm for shortest paths using a min-heap (`heapq`)
- Strongly Connected Components (SCCs) using Kosaraju's Algorithm (graph + reverse graph, finish-time ordering)

---

## How to Run
Each notebook is self-contained — open the Colab link, run all cells in order, and provide input as specified in each question's markdown cell (input via `input()` matching the given Input Format).
