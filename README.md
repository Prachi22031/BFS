# BFS
1. Initialization:
•	Choose a starting node from which to begin the traversal.
•	Create an empty queue and an empty list to keep track of visited nodes.
2. Enqueue and Start:
•	Enqueue the starting node into the queue.
•	Mark the starting node as visited.
3. Main BFS Loop:
•	While the queue is not empty, do the following steps:
•	Dequeue a node from the front of the queue. This is the current node being processed.
•	Process the current node (you might print it, collect information, or perform some specific task).
•	Explore the unvisited neighbours of the current node.
•	For each unvisited neighbour:
•	Mark the neighbour as visited.
•	Enqueue the neighbour into the queue.
4. Completion:
•	The BFS algorithm continues until the queue becomes empty. This ensures that all reachable nodes are visited exactly once.
