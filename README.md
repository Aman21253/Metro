This is a simple Java program that will take information (name) of the source station and the destination station, of Delhi Metro, from the user and display the fare and shortest metro route to reach the destination. It will also be having a metro map for commuter’s better navigation.

The idea is implemented using Graph and Heap data structures. The graph has nodes and edges. Nodes represent a metro station that will be containing certain information regarding that station like its name, its metro corridor, and the lines which it connects. Edges (the connection between two nodes) represent the distance between the two stations and the cost of each edge will be equal to the distance between the two of its connecting stations(nodes).

By using different algorithms like Dijkstra, breadth-first search, depth-first search, etc, the shortest path between the source station and the destination station is determined.According to the distance the fare is calculated


In metro.java
ArrayList
LinkedList
Stack
HashMap


In Heap.java
HashMap
ArrayList

The array data structure is implemented using ArrayList class which is a resizable array.It stores data in contiguous memory locations

Hashmap data structure is used to store key-value pairs.

The stack data structure required by the algorithm is implemented using linked list.It follows the principle Last In First Out(LIFO)

Heap is implemented with the help of ArrayList and HashMap.It is a tree based data structure where all elements of the tree are in a particular order.

Graph is a complex data structure containing vertices and edges connecting these vertices.This is implemented in the project with the help of ArrayList and HashMap.
