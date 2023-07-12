# Dijkstra’s Shortest Path Algorithm for Internet Routers

## Project Description
This project applies Dijkstra's Shortest Path algorithm to internet routers. The goal is to establish a cost-efficient network of interconnected routers by finding the shortest distances between them.

## Algorithm and System Requirements
The algorithm works by finding the path with the smallest total weight in a graph of interconnected routers. It takes inputs in the form of a list of sets representing the vertices and weights of edges. The algorithm utilizes a priority queue to efficiently determine the shortest paths.

## Code Overview
The code implements Dijkstra's algorithm using a priority queue based on Python's heapq module. It defines functions for pushing and popping items from the priority queue. The algorithm iterates through the vertices, selecting the lowest-cost paths. The distances between the starting vertex and all other vertices are calculated and returned.

## Complexity
The complexity of the algorithm can be approximated as O(n!), where n is the number of vertices. As the sample size increases, the running time of the algorithm also increases. This is due to the nested loop structure, which results in a polynomial increase in calculations.

## Conclusion
Dijkstra's algorithm is a powerful tool for finding the shortest paths in network systems. It can be applied to various domains, including internet routers, GPS systems, and game design. While the algorithm has limitations, such as requiring positive weights and a complete graph representation, it provides an efficient solution to the problem of establishing cost-efficient router networks.

For more details and code implementation, please refer to the attached PDF file.
