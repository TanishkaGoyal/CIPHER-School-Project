# CIPHER-School-Project
Cipher School Project
Certainly! Here are the key properties of a Binary Search Tree (BST):

1. **Node Structure**: Each node in a BST contains three components:
   - **Data**: The value stored in the node.
   - **Left Child**: A pointer/reference to the left subtree.
   - **Right Child**: A pointer/reference to the right subtree.

2. **Binary Tree**: A BST is a type of binary tree, meaning each node can have at most two children.

3. **Ordering Property**: For any given node in a BST:
   - All nodes in the left subtree have values less than the node's value.
   - All nodes in the right subtree have values greater than the node's value.

4. **Unique Values**: Typically, BSTs do not allow duplicate values. However, some variations can handle duplicates by placing equal values in either the left or right subtree consistently.

5. **Operations**:
   - **Insertion**: A new node is always added as a leaf node, ensuring the ordering property is maintained.
   - **Search**: The tree is traversed from the root to the target node, comparing values at each step.
   - **Deletion**: Removing a node can be complex due to the need to maintain the BST properties. There are three cases:
     - Node with no children (leaf node): Simply remove the node.
     - Node with one child: Remove the node and link its child directly to its parent.
     - Node with two children: Find the in-order successor (smallest value in the right subtree) or in-order predecessor (largest value in the left subtree) to replace the node, 
     then delete the successor/predecessor.

6. **Traversal**:
   - **InOrder Traversal**: Visits nodes in ascending order (left-root-right).
   - **PreOrder Traversal**: Visits nodes in root-left-right order.
   - **PostOrder Traversal**: Visits nodes in left-right-root order.

7. **Balanced vs. Unbalanced**:
   - **Balanced BST**: The height difference between the left and right subtrees of any node is minimal, leading to efficient operations. Examples include AVL trees and Red-Black trees.
   - **Unbalanced BST**: Can degrade to a linked list in the worst case, where operations become linear in time complexity.

8. **Height and Depth**:
   - **Height**: The length of the longest path from the node to a leaf.
   - **Depth**: The length of the path from the root to the node.

9. **Time Complexity**:
   - **Average Case**: O(log n) for insertion, deletion, and search operations.
   - **Worst Case**: O(n) for insertion, deletion, and search operations in an unbalanced BST.

These properties make BSTs efficient for various dynamic set operations such as maintaining a sorted list of items, and supporting fast lookups, insertions, deletions, and range queries.
