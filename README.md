# UFLP Optimization Algorithms

## Overview

This project focuses on the **implementation and performance analysis of optimization algorithms** for solving the **Uncapacitated Facility Location Problem (UFLP)**, a classical combinatorial optimization problem with applications in logistics, supply chain design and resource allocation.

The goal was to study how different algorithmic approaches perform in terms of **solution quality, computational efficiency and scalability**, comparing heuristic, metaheuristic and exact methods.

The project was developed in an academic context for an Algorithm Analysis and Optimization course.

---

## Project Context

The original assignment specification and the full academic report are available in the `docs/` folder:

* Project specification (assignment brief)
* Final academic report with theoretical background, methodology, results and conclusions

These documents provide detailed context about the objectives, methodology and experimental evaluation.

---

## Implemented Algorithms

### Heuristic Methods

* **Swap heuristic** – Iterative improvement by swapping facility states
* **Switch heuristic** – Incremental local search adjusting individual facilities

These approaches prioritise speed while providing near-optimal solutions.

---

### Metaheuristic Method

* **Variable Neighborhood Search (VNS)**
  Designed to escape local optima by exploring multiple neighbourhood structures and refining candidate solutions.

This method showed strong solution quality, especially for larger instances.

---

### Exact Method

* **Branch and Bound**
  Guarantees optimal solutions but has high computational cost and limited scalability for large problem instances.

---

## Performance Analysis

The project includes comparative analysis based on:

* Execution time
* Solution deviation from optimal values
* Scalability across different instance sizes

Results demonstrate the typical trade-off between precision and computational cost when choosing optimization strategies.

---

## Technologies Used

* Java
* Gradle build system
* Algorithm analysis techniques
* Benchmark datasets (including OR-Library instances)

---

## Data and Documentation

* `data/` → Benchmark problem instances and reference optimal values
* `docs/` → Assignment specification and full academic report

---

## My Contribution

Although this was officially a group project (five members), I was primarily responsible for:

* Most of the algorithm implementation
* Performance testing setup
* Significant parts of the experimental analysis

This repository mainly reflects my individual technical contribution to the project.

---

## Learning Outcomes

This project strengthened practical knowledge in:

* Combinatorial optimization
* Heuristic and metaheuristic algorithm design
* Performance evaluation of algorithms
* Trade-offs between exact and approximate methods
* Algorithm scalability considerations

---

## Possible Future Improvements

* Parallel implementations for performance gains
* Additional metaheuristics (e.g., genetic algorithms, ant colony optimization)
* Visualization of solution quality evolution
* Real-world logistics dataset integration

---

