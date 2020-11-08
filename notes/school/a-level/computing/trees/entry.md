---
title: "Computing - Trees"
date: "2020-11-06 12:30"

tags: ["@?computing", "@?public", "@?data-types"]
---

##### What is a tree??
A connected, undirected graph with no cycles.

##### What is a binary tree??
A rooted tree where each node has at most two children.

##### What type of data type is a tree??
An Abstract Data Type.

##### What three terms are used for both actual trees and computer science trees??
Root, branches and leaves.

##### What is the definition of the root of a tree??
The only node that doesn't have a parent node.

##### What is the definition of a child of a node??
The nodes that come after a parent.

##### What are the definition of a leaf of a tree??
The nodes that don't have children.

##### What is the definition of a subtree??
The tree formed when you think of a child as its own rooted tree.

##### What kind of relationship does a tree represent??
A hierachy.

##### What's another name for leaves of a tree??
Terminal nodes.

##### When constructing a binary tree for strings, how should you sort the tree??
Strings alphabetically before a root should go on the left, strings after should go on the right.

##### To store a binary tree, what three things should you store for each node??
* The left pointer
* The right pointer
* The data itself

##### Why is traversal best done recursibely
Any node with children can be thought of the root of a subtree.

##### What are the three depth-first traversal stratagies??
* Pre-order
* Post-order
* In-order

##### What are the 3 steps for pre-order traversal??
* Root
* Left subtree
* Right subtree

##### What are the 3 steps for post-order traversal??
* Left subtree
* Right subtree
* Root

##### What's another way to think about post-order traversal??
A bottom-up traversal.

##### What are the 3 steps for in-order traversal??
* Left subtree
* Root
* Right subtree

##### Where should the dot go for pre-order traversal??
Left.

##### Where should the dot go for post-order traversal??
Right.

##### Where should the dot go for in-order traversal??
Underneath.

##### What's the easy way to perform a traversal algorithm by hand??
Trace around the tree visiting dots as specified by the traversal method.

##### What does the traced version of ![PHOTO](tree-pre-order.png) look like??
![PHOTO](tree-pre-order-filled.png)

##### What does the traced version of ![PHOTO](tree-post-order.png) look like??
![PHOTO](tree-post-order-filled.png)

##### What does the traced version of ![PHOTO](tree-in-order.png) look like??
![PHOTO](tree-in-order-filled.png)

##### What is special about in-order traversal??
It recieves the data according to its inherent sequence.

##### If you use in-order traversal on an alphabetically sorted tree, what is special about the result??
The nodes are visited in alphabetical order.
