# Breadth-first search

- Read 3.5, pages 125-128
    - How does breadth-first search traverse the vertices of a graph? How does it differ to depth-first search?
    - Breadth-first search uses a queue to keep track of the vertices that need to be traversed. Why is the use of a queue (as opposed to a stack) important?
    - Perform a BFS and draw the breadth-first forest for the graph of figure 3.11.
    - What are **tree edges** and **cross edges** in a BFS?
    - Explain why cross edges in a BFS connect only vertices on the same or adjacent level in the breadth-first forest.
    - Write the pseudocode for BFS.
    - At what points during the algorithm does the queue become empty?
    - How can we use BFS to detect cycles in the graph?
    - We want to augment the BFS algorithm to record the "level" of each vertex, i.e. how many steps from the root it takes to get to it in the BFS forest. What do we need to change in the algorithm?
    - How can we use BFS to record the distance of each vertex from a root vertex?
    - Carry out BFS for the graph in exercise 3.5.1.
    - Practice problems: 3.5.10, solve using BFS instead of DFS.
