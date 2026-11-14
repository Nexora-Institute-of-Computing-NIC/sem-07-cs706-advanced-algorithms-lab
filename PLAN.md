# CS706 — Advanced Algorithms Lab — PLAN

**Semester:** 7 · **Credits:** 2 · **Level:** Advanced-Professional
**Theory:** 0 hrs · **Lab:** 45 hrs · **Tools:** C++ or Python, competitive programming platforms, algorithm libraries

## Course Format
Pure hands-on. Beyond the fundamentals of CS301, this lab covers advanced algorithm design — the algorithms that appear in real systems and hard coding contests. Every lab is a working implementation plus benchmarks and analysis.

## Lab Modules

### Module 1 — Advanced Data Structures (3 labs)
1. Segment tree — range sum, range min, point updates
2. Lazy propagation segment tree — range updates
3. Fenwick tree (BIT) — prefix sums and 2D variants

### Module 2 — Advanced Graph Algorithms (3 labs)
4. Strongly connected components — Kosaraju and Tarjan
5. Maximum flow — Dinic's algorithm
6. Bipartite matching — Hopcroft-Karp

### Module 3 — Advanced String Algorithms (2 labs)
7. Suffix array and LCP array construction
8. Suffix automaton for pattern queries

### Module 4 — Advanced Number Theory (2 labs)
9. Chinese Remainder Theorem with non-coprime moduli
10. Miller-Rabin primality + Pollard's rho factorisation

### Module 5 — Approximation and Randomisation (2 labs)
11. Approximation algorithms — vertex cover and set cover
12. Randomised algorithms — quickselect, reservoir sampling, Karger's min-cut

### Module 6 — Advanced Dynamic Programming and Geometry (3 labs)
13. Bitmask DP — TSP variants
14. Convex hull trick — DP optimisation
15. Computational geometry — convex hull, line intersection, point-in-polygon

## Weekly Structure
Each lab = working code + `REPORT.md` covering:
- Problem statement
- Approach and complexity analysis
- Correctness argument (short)
- Benchmark — runtime across input sizes
- One alternative considered and rejected (with reason)

## Assessment

| Component | Weight |
| :--- | :---: |
| Weekly reports (15) | 60% |
| Code correctness (all tests passing) | 20% |
| Final — an advanced algorithm project | 20% |

## Deliverable Layout
advanced-algorithms-lab/
├── code/
│ ├── lab-01-segment-tree/
│ ├── lab-02-lazy-segtree/
│ └── ...
├── reports/
│ ├── lab-01-segment-tree.md
│ └── ...
└── final-project/
├── README.md
└── solution.py

text

## Benchmarks to Include (every lab)

- Smallest input (edge case)
- Typical input
- Worst case for the algorithm
- Comparison against a naive solution on small inputs
