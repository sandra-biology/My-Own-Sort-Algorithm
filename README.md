# My-Own-Sort-Algorithm

While I was working with binary tree traversal algorithms, I saw that general inorder method returns sort list of node
values for binary search trees. I realized that I could use this method for general sort algorithm. For this I just needed
to create binary search tree out of list of elements to be sorted and call the Tree.inorder method to sort the list.

I realized it would be even more useful if I could compile the Tree.inorder method with other methods needed for this
algorithm. So I wrote a class that would utilize this sort algorithm. The main method in this class is my sort method
that takes a list (that we want to sort) and using inorder traversal algorithm returns the sorted list.

This class contains two methods that I used for testing creation of tree using list given to sort method as input.
