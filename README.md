# What I learned from this project  
At the end of this project you are expected to be able to explain to anyone, without the help of Google:  
---   

**What is a binary tree?**  
*Each node has at most 2 children.
Strict binary tree has either 2 or 0 children.
Complete binary tree is all nodes are filled and as left as possible.
2^n and n is the levels. levels start at 0. we can have at max n number of nodes at lvl n.
Perfect binary tree is everything is filled.
Max number of nodes in a perfect binary is 2^(n+1) - 1.
Height is a Logbase2 n for complete binary and log base2 (n+1) for perfect binary tree.
A 2 to the 100th power will have a time of log base 2 100 which is just 100.
Height of tree is one less than the longest number of consec nodes.*  

*If height is minimized then cost of operations is lowered. Balance is good.
Implement binary trees using dynamically created nodes. Store addresses, linked via pointers. Or we can store the binary tree in an array.
Array only works for a complete binary tree. left child is 2i+1 and right child is 2i+2. I is the index or levels. Array that is a heap is like this.*



**What is the difference between a binary tree and a Binary Search Tree?**  
*Binary tree is a linked data structure where each node can point to up to 2
kids and a BST or binary search tree if the key of the node is smaller than all
its right subtree and greater than all its left subtree.*  

**What is the possible gain in terms of time complexity compared to linked lists?**  
*Singly linked list has a O(n) access and search time complexity with a 0(1) for insertion and deletion. This is for average and worse case scenarios.*  

*But a BST has log(n) for access and search which is great but the tradeoff is the insertion and deletion is not O(1) like linked lists but also log(n). And worst case scanarios for BST is O(n) for accessing, searching, inserting, and deleting.*  


**What are the depth, the height, the size of a binary tree?**  
*The depth is the number of edges from the node to the root.
The height is the number of edges on the longest path. The size is the number of nodes on the tree. Edges are connections.*  


**What are the different traversal methods to go through a binary tree?**  
*inorder, preorder, and postorder.
left root right, root left right, and left right root.*  


**What is a complete, a full, a perfect, a balanced binary tree?**  
*A complete is every level is filled and complete and as left as possible. Also called almost complete and nearly complete binary tree.
A full tree is a tree where all nodes have 0 or 2 children. No singles allowed.
Perfect is perfect.
A balanced binary tree is balanced. Left and right subtrees differ in height by no more than 1. Basically the same height everywhere..*  



## Each scripts and their output  
* Script 0 - Write a function that creates a binary tree node.    
* Script 1 - Write a function that inserts a node as the left-child of another node.  
* Script 2 - Write a function that inserts a node as the right-child of another node.  
* Script 3 - Write a function that deletes an entire binary tree.  
* Script 4 - Write a function that checks if a node is a leaf.    
* Script 5 - Write a function that checks if a given node is a root.    
* Script 6 - Write a function that goes through a binary tree using pre-order traversal.  
* Script 7 - Write a function that goes through a binary tree using in-order traversal.  
* Script 8 - Write a function that goes through a binary tree using post-order traversal.  
* Script 9 - Write a function that measures the height of a binary tree.  
* Script 10 - Write a function that measures the depth of a node in a binary tree.  
* Script 11 - Write a function that measures the size of a binary tree.  
* Script 12 - Write a function that counts the leaves in a binary tree.  
* Script 13 - Write a function that counts the nodes with at least 1 child in a binary tree.  
* Script 14 - Write a function that measures the balance factor of a binary tree.  
* Script 15 - Write a function that checks if a binary tree is full.  
* Script 16 - Write a function that checks if a binary tree is perfect.  
* Script 17 - Write a function that finds the sibling of a node.  
* Script 18 - Write a function that finds the uncle of a node.  
* Script 19 - Write a function that finds the lowest common ancestor of two nodes.  
* Script 20 - Write a function that goes through a binary tree using level-order traversal.  
* Script 21 - Write a function that checks if a binary tree is complete.  
* Script 22 - Write a function that performs a left-rotation on a binary tree.  
* Script 23 - Write a function that performs a right-rotation on a binary tree.  
* Script 24 - Write a function that checks if a binary tree is a valid Binary Search Tree.  
* Script 25 - Write a function that inserts a value in a Binary Search Tree.  
* Script 26 - Write a function that builds a Binary Search Tree from an array.  
* Script 27 - Write a function that searches for a value in a Binary Search Tree.  
* Script 28 - Write a function that removes a node from a Binary Search Tree.  
* Script 29 - Quiz answers.  
* Script 30 - Write a function that checks if a binary tree is a valid AVL Tree.  

## Resources
[Binary tree (note the first line: Not to be confused with B-tree.)](https://en.wikipedia.org/wiki/Binary_tree)

[Data Structure and Algorithms - Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)

[Tree Traversal](https://www.programiz.com/dsa/tree-traversal)

[Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree)

[Data structures: Binary Tree
](https://www.youtube.com/watch?v=H5JubkIy_p8)

