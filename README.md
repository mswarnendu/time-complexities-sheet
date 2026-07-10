# Common Time Complexities

## Typical Operations

| Operation | Time Complexity |
|-----------|-----------------|
| Mathematical formula (direct calculation) | **O(1)** |
| Binary search | **O(log n)** |
| Sorted set/map or priority queue (per operation) | **O(log n)** |
| Naive primality test | **O(√n)** |
| Trial-division prime factorization | **O(√n)** |
| Read `n` inputs | **O(n)** |
| Iterate through an array/list of `n` elements | **O(n)** |
| Sorting (`std::sort`, Merge Sort, `Collections.sort`, `Arrays.sort` for objects) | **O(n log n)** |
| Java primitive `Arrays.sort` (Dual-Pivot Quicksort, worst case) | **O(n²)** |
| Iterate through all subsets of size `k` | **O(nᵏ)** |
| Iterate through all triplets | **O(n³)** |
| Iterate through all subsets | **O(2ⁿ)** |
| Iterate through all permutations | **O(n!)** |

---

# Competitive Programming Complexity Guide

These are conservative estimates for standard competitive programming time limits (roughly 1–3 seconds).

| Maximum `n` | Typical Acceptable Complexity |
|-------------|-------------------------------|
| `n ≤ 10` | **O(n!)**, **O(n⁷)**, **O(n⁶)** |
| `n ≤ 20` | **O(2ⁿ · n)**, **O(n⁵)** |
| `n ≤ 80` | **O(n⁴)** |
| `n ≤ 400` | **O(n³)** |
| `n ≤ 7,500` | **O(n²)** |
| `n ≤ 70,000` | **O(n√n)** |
| `n ≤ 500,000` | **O(n log n)** |
| `n ≤ 5,000,000` | **O(n)** |
| `n ≤ 10¹⁸` | **O(log² n)**, **O(log n)**, **O(1)** |

---

# Quick Reference

| Complexity | Typical Use |
|------------|-------------|
| **O(1)** | Math formulas, array indexing, hash map lookup (average) |
| **O(log n)** | Binary search, balanced BSTs, heaps |
| **O(√n)** | Trial-division primality testing, factorization |
| **O(n)** | Single pass over data |
| **O(n log n)** | Efficient sorting, divide & conquer |
| **O(n²)** | Double nested loops |
| **O(n³)** | Triple nested loops, Floyd–Warshall |
| **O(2ⁿ)** | Backtracking over all subsets |
| **O(n!)** | Enumerating all permutations |
