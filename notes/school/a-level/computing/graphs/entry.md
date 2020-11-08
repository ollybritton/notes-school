---
title: "Computing - Graphs"
date: "2020-11-05 11:05"

tags: ["@?computing", "@?public"]
---

##### In summary, what is a graph??
An abstract data type representing complex relationships.

##### What is an undirected graph??
A graph where the edges don't specify a direction.

##### What does an edge represent in a graph??
A relationship between two nodes.

##### What is an edge weight??
A numerical value associated with an edge.

##### What does an edge weight commonly represent on a graph representing a map??
The distances between two places.

##### What is a directed graph??
A graph where relationships can point one way only.

##### What is the technical definition of a graph??
A set of nodes connected by edges.

##### What's another name for nodes in a graph??
Verticies.

##### What's another name for edges in a graph??
Arcs.

##### What's another name for a directed graph??
A digraph.

##### What are the two ways of representing a graph??
* Adjancency matrix
* Adjancency list

##### How does an adjancency matrix represent a graph??
A two-dimensional array where a value at $[\text{row}, \text{column}]$ represents a connection.

##### In the adjancency matrix \\[ \begin{table}[]\begin{tabular}{llll}  & A & B & C \\ A &  & 1  &   \\ B &   &   &   \\ C &   & 1 &  \end{tabular}\end{table}\\], what does the second cell represent??
A connection from $B$ to $A$.

##### What is special about the adjancency matrix for an undirected graph??
The matrix will be symmetric.

##### What is the advantage of an adjacency matrix??
It's simple to work with.

##### What is the disadvantage of an adjancency matrix??
A sparse graph will have a lot of empty cells which wastes memory space.

##### How does an adjacency list represent a graph??
A dictionary containing the nodes and list of the other nodes it points to.

##### What is the advantage of an adjacency list??
It only stores the connections that exist so it's more space-efficient.

##### What's the best way to represent a large, sparse graph??
Using an adjacency list.

##### What does connected mean in the context of graphs??
Each node is linked to another node.

