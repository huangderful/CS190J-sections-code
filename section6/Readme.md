# Section Summary
---
Reviewed Simplicial Complexes:
Simplex definition, Boundary Operator, Hodge Laplacian, TDA

In class problems:
What are 1,2,3 d simplex?
What is a Betti number and what does it tell you?
How does Vietoris Rips Filtration work?
What is a feature?

# Recommended Problems
---
### Textbook problems

### Other problems
---
You are given the following weighted undirected graph, where vertices represent 0-simplices and edges represent 1-simplices. Each edge has a weight indicating when it appears during a filtration. As the filtration parameter ε increases, you add all edges whose weight is ≤ ε. Whenever a triangle is formed, add the corresponding 2-simplex immediately at that ε.

Graph Description:
Let the vertex set be
V = {A, B, C, D}

And the weighted edge set is:

AB: weight = 1

AC: weight = 2

BC: weight = 3

BD: weight = 4

CD: weight = 5

AD: weight = 6

Tasks:
For ε = 0, 1, 2, ..., 6, build the simplicial complex filtration by applying Vietoris Rips Filtration:

1. Adding edges with weight ≤ ε

2. Adding filled-in triangles (2-simplices) when a triangle is fully formed

3. For each ε, count:

The number of connected components (β₀)

The number of 1-dimensional holes (β₁)

4. Draw the barcode diagram for β₀ and β₁
5. Draw the Persistence diagram for β₀ and β₁.
---
6. Explain why using TDA is better than naive approach of a distance threshold in the polling example.
7. What is the hodge laplacian and what is its relation to the boundary operator?
# Lecture Slides
---
https://ucsb.instructure.com/courses/26664/files/folder/Lecture%20Slides?preview=5001976
https://ucsb.instructure.com/courses/26664/files/folder/Lecture%20Slides?preview=5001979
