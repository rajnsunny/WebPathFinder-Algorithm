# Pathfinding Visualizer

Welcome to Pathfinding Visualizer! I built this application because I was fascinated by pathfinding algorithms, and I wanted to visualize them in action. I hope that you enjoy playing around with this visualization tool just as much as I enjoyed building it. You can access it here (use Google Chrome!): https://rajnsunny.github.io/WebPathFinder-Algorithm/

## Meet the Algorithms

This application supports the following algorithms: 

**Dijkstra's Algorithm** (weighted): the father of pathfinding algorithms; guarantees the shortest path

**A* Search** (weighted): arguably the best pathfinding algorithm; uses heuristics to guarantee the shortest path much faster than Dijkstra's Algorithm; https://www.geeksforgeeks.org/a-search-algorithm/

**Greedy Best-first Search** (weighted): a faster, more heuristic-heavy version of A*; does not guarantee the shortest path;https://www.geeksforgeeks.org/best-first-search-informed-search/

**A Algorithm** (weighted): a mixture of Dijkstra's Algorithm and A*; does not guarantee the shortest-path

**B Algorithm** (weighted): the faster, more heuristic-heavy version of Swarm; does not guarantee the shortest path

**Bidirectional A Algorithm** (weighted): Swarm from both sides; does not guarantee the shortest path

**Breath-first Search** (unweighted): a great algorithm; guarantees the shortest path

**Depth-first Search** (unweighted): a very bad algorithm for pathfinding; does not guarantee the shortest path

On top of the pathfinding algorithms listed above, I implemented a **Recursive Division** Maze Generation algorithm.

## More about the Swarm Algorithm

 The algorithm is essentially a mixture of Dijkstra's Algorithm and A* Search; more precisely, while it converges to the target node like A* , it still explores quite a few neighboring nodes surrounding the start node like Dijkstra's. The algorithm differentiates itself from A* through its use of heuristics: it continually updates nodes' distance from the start node while taking into account their estimated distance from the target node. This effectively "balances" the difference in total distance between nodes closer to the start node and nodes closer to the target node. 
