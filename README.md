# My-Own-Sort-Algorithm


When working with trees, I saw that depth-first traversal algorithms all operate recursively. Since for Binary Search
Tree (BST) the node with the lowest value is the leftmost node on the lowest level, inorder traversal prints the value
of that node first. 

This led to me discovering that when we are dealing with a Binary Search Tree the inorder traversal
algorithm returns list of node values that is already sorted. Therefore, for Binary Search Tree we can use
inorder traversal algorithm when we need to sort a list.

With this in mind, I wrote a class that would utilize this algorithm. The main method in this class is my sort method
that takes a list (that we want to sort) and using inorder traversal algorithm returns the sorted list.
