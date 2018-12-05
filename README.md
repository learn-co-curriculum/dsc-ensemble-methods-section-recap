
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 28

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:
* One way of modeling certain types of data is using a graph
* A graph is comprised of nodes (sometimes called vertices or points) connected by edges (sometimes called arcs or lines)
* Edges can be uni-or bidirectional (I buy from a local suopermarket, but the supermarket may not buy from me - unless I run a dairy farm)
* Edges can also be weighted (length of friendship, distance between two locations, how many stars someone rated a movie, etc)
* Nodes are adjacent if there is at least one edge connecting them
* In an undirected graph, the degree of a node is the number of edges connected to the node
* In a directed graph, the indegree is the number of edges arriving at the node and the outdegree is the number of edges departing the node
* An isolated node is one with a degree of 0
* A path is a specific way to get from one node to another via 1..n edges
* Two ways of serializing (saving to simple text files) graph data are edge lists and adjacency matrices
* Dijkstra's algorithm is a popular algorithm for finding the shortest path between two given nodes
* Degree centrality refers to the percentage of nodes in a graph that a given node is directly connected to
* Closeness centrality measures how many edges a you'd have to traverse from a starting node to reach every other node in the network (think of it as the "average distance" to all other nodes)
* Betweenness centrality measures the number of times a node acts as a brideg along the shortest path between two other nodes
* Eigenvector centrality is high if a node is connected to many well connected nodes
* Bipartite graphs are graphs where nodes in each of two sets have edges connecting to nodes in the other set but no nodes in their own set
* Communities (also called partitions, clusters and groupings) are sets of nodes that are more densely connected to each other than to the rest of the graph
* The Grivan-Newman algorithm can be used to detect communbities by progressively removing edges from the original graph
* A clique is a subset of nodes in an undirected graph where every two distinct nodes are adjacent
* A k-clique community is the union of all cliques of size k that can be reached through adjacent (sharing k-1 nodes) k-cliques
* The island method can be used to identify highly connected communities
* An ego network consists of a focal node ("ego") and the nodes to whom the ego node is directly connected to (these are called "alters") plus the edges, if any, among the alters

