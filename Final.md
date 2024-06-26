# Exercises

## Exercise 1

**Question:** What is the smallest number of colors you need to properly color the vertices of K_{4,5}? That is, find the chromatic number of the graph.

**Solution:** \( K_{4,5} \) is a complete bipartite graph. In a complete bipartite graph \( K_{m,n} \), the chromatic number is 2, since you can color all vertices in one set with one color and all vertices in the other set with a different color. Thus, the chromatic number of \( K_{4,5} \) is 2.

<img width="421" alt="Screenshot 2024-06-10 at 9 15 59 AM" src="https://github.com/dudegod1/csc208/assets/77406625/63d961ed-02ff-4828-afd2-703a16cf6a31">

## Exercise 2

**Question:** Draw a graph with chromatic number 6 (i.e., which requires 6 colors to properly color the vertices). Could your graph be planar? Explain.

**Solution:**

1. **Graph with Chromatic Number 6:** A common example of a graph with a chromatic number of 6 is the complete graph K_{6}.

2. **Planarity Check using the Four Color Theorem:** The Four Color Theorem states that any planar graph can be colored with at most 4 colors such that no two adjacent vertices share the same color.

Since the Four Color Theorem limits the chromatic number of any planar graph to at most 4, a graph that requires 6 colors to properly color its vertices cannot be planar. Therefore, \( K_6 \) is not planar, as it exceeds the 4-color limit set by the Four Color Theorem.

<img width="295" alt="Screenshot 2024-06-10 at 8 02 40 PM" src="https://github.com/dudegod1/csc208/assets/77406625/7f1157fa-5498-4af4-858d-eaa456b24140">

