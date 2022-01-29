# Class Fifteen

[Home](https://daviey52.github.io/reading-notes/)

Binary Trees, Binary Search and K-aray Trees

## Commonly used terminology

Root – is the node at the beginning of the tree
K – a number that specifies the maximum number of children any node may have in a k-ary tree
Left and right – references to child node in a binary tree
Edge – This is the link between a parent and child node
Leaf – A node that does not have any children
Traversing a tree enable us to search for a node, print the content of a tree and much more. There are two wats of traversals when it comes to trees. 1. Depth First 2. Breadth first

### Depth First

This is when we prioritize going through the depth of the tree first. Some of the main methods used
1.Pre-order : root >> left >> right
2.  In-Order :  left >> root >> right
3. Post-order:  left >> right >> root
The most common way to traverse through a tree is by use of recursive. The common thing with all these traversals is when you are looking at the root node.

### Breadth First

This traversal iterates through the tree by going through each level of the tree node-by-node.
Traditionally this method uses a queue instead of of recursive stack method used by depth first.

### Binary Trees Vs K-array Trees

Trees can have any number of children per node, but binary trees restrict the number of children to two. There is no specific sorting order for a binary tree. Node can be added into a binary tree wherever space allows.
If Nodes have more than 2 child nodes, we call the tree that contains them a K-ary tree. We use K to refer to the maximum number of children that each node is able to have.
Traversing a K-ary tree requires a similar approach to the breadth first traversal. We are still pushing nodes into a queue though now we are moving down a list of children of length k, instead of checking for the presence of a left and a right child.
Adding a node
One main strategy is adding a new node to a binary tree by filling all “child spot” from the top down. We leverage the use of breadth first traversal. We fill child slots from left to right
Big 0
Inserting a node
Big 0 time: 0(n)
Big 0 space :0(w)

### Binary Search Tree

This is a type of tree that have nodes organized in a manner where all values smaller than the root are placed to the left and all values larger than the root are placed to the right. Searching a BST is done by comparing the node you are searching for against the root of the tree or sub-tree. The best way is by utilizing a while Loop.
Big 0
Big 0 time: 0(h)
Big 0 space :0(1)
