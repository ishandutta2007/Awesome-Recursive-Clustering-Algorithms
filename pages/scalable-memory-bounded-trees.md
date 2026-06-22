# Scalable Memory-Bounded Trees (BIRCH / CURE)

## Overview
These algorithms address the memory limitations and computational bottlenecks ($O(N^2)$) of classic hierarchical clustering, introducing tree-building features to compress streaming raw data.

## Detailed Information
- **BIRCH:** Uses a Clustering Feature (CF) Tree to summarize data distribution.
- **CURE:** Represents clusters using a set of well-scattered representative points.
- **Year First Used:** 1996
- **Foundational Paper:** [BIRCH: An Efficient Data Clustering Method for Very Large Databases](https://doi.org/10.1145/233269.233324)

## Diagram
```mermaid
graph TD
    Root[CF Tree Root] --> Node1[CF Node 1]
    Root --> Node2[CF Node 2]
    Node1 --> Leaf1[Leaf Entry 1]
    Node1 --> Leaf2[Leaf Entry 2]
```

[Back to README](../README.md)
