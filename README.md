Download Link: https://assignmentchef.com/product/solved-solvedhomework-3-binarynode-solution
<br>
Write the 5 methods that are next to your name. All methods must be added tothe BinaryNode class. Feel free to use the methods in that class andto write your own private helper methods. Follow the same rules for submittingthe homeworks as in Hw#1 and Hw#2.

Method 1. Add the method prePlusIn to the BinaryNode class.

The method has the header

public static

and takes as input the preorder and the inorder traversals of a the itemsof a binary tree and constructs a tree with these traversals. It returnsthe root of the tree. Assume that none of the two traversals has duplicateitems. The method throws an IllegalArgumentException if it is not possibleto construct the tree.

Method 2. Add the method postPlusIn to the BinaryNode class.

The method has the header

public static

and takes as input the postorder and the inorder traversals of a binary tree.and constructs a tree that with these traversals. It returns the rootof the tree. Assume that none of the two traversals has duplicateitems. The method throws an IllegalArgumentException if it is not possibleto construct the tree.

Method 3. Add the method

public static

that takes as input the inorder traversal and the traversal by levels ofa binary tree and constructs the tree. It returns the root of the tree. Assume thatnone of the two traversal have duplicate items.Throw an IllegalArgumentException if this cannot be done.

Method 4. Add the method

public void iterativePostOrder()

that prints the nodes of the tree with root this in postorder,without using recursion. Use a stack.

Method 5. Add the method

public void printByLevels()

That prints the nodes of the tree by levels. Use a queue.

Method 6. Add the method

public void iterativeInOrder()

that prints the nodes of the tree with root this in inorder,without using recursion. Use a stack.

Maethod 7. Add the method

public BinaryNode

that finds the parent of the node n in this tree.If n = null throw an IllegalArgumentException.If n = this or n does not occur in the tree return null.

Method 8. Two trees are equal if they have the same address set andthe values at the same address are equal.Write the method

public boolean equals(BinaryNode

that returns true if the tree r is equalto this and false otherwise. Some of the items may be null. Use equalsto check for equality.

Method 9. Two trees are isomorphic if one of them can be derived from the otherby swapping some of the left and right children.Write the method

public boolean isomorphic(BinaryNode

that returns true if the tree r is isomorphic to this and false otherwise.Some of the items may be null. Use the equals method to check for equality.

Method 10. Write the method

public static

that returns a longest path in the tree root. The first item ofthe array list is the value of the root.