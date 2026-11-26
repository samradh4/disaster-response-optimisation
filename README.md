# Disaster Response Optimisation System — ACE Programming
Open index.html in a modern browser. No installation or internet required.
Report incidents, run dispatch, toggle roads by clicking them, and complete assignments. Reset restores the sample scenario.
Algorithm: Dijkstra on an undirected weighted graph; priority score = 20 × severity + min(people affected, 100). Greedy nearest available reachable team assignment in descending priority order. Baseline uses the first available reachable team for each actual assignment, not an independent full-system simulation. Road changes recalculate from the original dispatch sector (no movement simulation). All data is illustrative and resets on refresh. Not for real-world emergency use.
This is a standalone browser implementation, not an update to the earlier Python source, which was not provided.
