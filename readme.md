# Advent of Code

Here are my Python solutions to Advent of Code 2024, which was my first year solving it. Each day's solution (both parts) is in a Jupyter Notebook, and for the most part I tried to avoid importing packages that are not a part of the Python standard library. There are exceptions to this in my solutions to day 13 (where I imported `sympy` as an equation solver) and day 14 (where I imported `matplotlib`, `numpy`, and `IPython` to visualize the Easter egg.) Beyond that, most problems can be solved without any external imports, including day 23, which I solved without using an external graph library.

## Problem Ratings by Day

This is solely my own experience and the rating criteria themselves are inherently subjective. Each criterion is rated out of 5 stars. The "fun" rating refers to how much fun I personally had solving these, and the "idea" rating refers how to creative I think the idea behind the problem is, based on what I imagine the creator's perspective was.

### AoC 2024

| **#** | **Fun** | **Difficulty** | **Idea** | **Things I learned/used for the first time** |
| ------- | ------- | -------------- | -------- | -------------------------------------------- |
| 1 | ⭐️ | ⭐️ | ⭐️ | -- |
| 2 | ⭐️ | ⭐️ | ⭐️ | -- |
| 3 | ⭐️⭐️ | ⭐️ | ⭐️⭐️⭐️ | -- |
| 4 | ⭐️⭐️ | ⭐️ | ⭐️⭐️ | Using regex to solve this problem (not my solution) |
| 5 | ⭐️⭐️⭐️⭐️ | ⭐️⭐️ | ⭐️⭐️⭐️ | More efficient ways to implement this kind of sorting (not my solution) |
| 6 | ⭐️ | ⭐️ | ⭐️⭐️ | -- |
| 7 | ⭐️⭐️⭐️ | ⭐️ | ⭐️⭐️ | Using `itertools` to generate permutations/combinations |
| 8 | ⭐️⭐️⭐️ | ⭐️⭐️ | ⭐️⭐️⭐️ | -- |
| 9 | ⭐️⭐️⭐️ | ⭐️ | ⭐️⭐️⭐️ | -- |
| 10 | ⭐️⭐️⭐️⭐️ | ⭐️ | ⭐️⭐️ | -- |
| 11 | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️ | -- |
| 12 | ⭐️⭐️ | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️ | Stronger pattern recognition skills apparently |
| 13 | ⭐️⭐️⭐️ | ⭐️ | ⭐️ | Using `sympy` to solve equations |
| 14 | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️ | ⭐️⭐️⭐️⭐️ | -- |
| 15 | ⭐️⭐️⭐️ | ⭐️⭐️⭐️ | ⭐️⭐️⭐️ | -- |
| 16 | ⭐️⭐️⭐️ | ⭐️⭐️⭐️ | ⭐️⭐️ | Manual implementation of [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra's_algorithm) |
| 17 | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️⭐️ | More pattern recognition skills and possibly some reverse engineering |
| 18 | ⭐️⭐️ | ⭐️⭐️ | ⭐️ | -- |
| 19 | ⭐️⭐️ | ⭐️ | ⭐️ | -- |
| 20 | ⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️ | [Manhattan distance](https://en.wikipedia.org/wiki/Taxicab_geometry) as a grid distance metric |
| 21 | ⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️ | -- |
| 22 | ⭐️⭐️ | ⭐️⭐️ | ⭐️ | -- |
| 23 | ⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️ | ⭐️⭐️ | Manual implementation of the [clique problem](https://en.wikipedia.org/wiki/Clique_problem) |
| 24 | ⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️⭐️ | ⭐️⭐️⭐️⭐️⭐️ | Even more pattern recognition skills |
| 25 | ⭐️⭐️⭐️⭐️⭐️ | ⭐️ | ⭐️ | -- |
