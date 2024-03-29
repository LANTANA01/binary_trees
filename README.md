0x1D. C - Binary trees.


A binary tree is a hierarchical data structure where each node has at most two children: a left child and a right child.

1. **Node Structure**:
   - A binary tree node is represented by a structure containing:
     - `data`: The value stored in the node.
     - `left`: A pointer to the left child node (or `NULL` if no left child).
     - `right`: A pointer to the right child node (or `NULL` if no right child).

2. **Types of Binary Trees**:
   - **Full Binary Tree**: Every internal node has either two or no children.
   - **Perfect Binary Tree**: Every internal node has exactly two child nodes, and all leaf nodes are at the same level.
   - **Complete Binary Tree**: All levels are completely filled, and leaf elements lean towards the left.
   - **Degenerate (Pathological) Tree**: Each node has only one child (either left or right).
   - **Balanced Binary Tree**: Difference in height between left and right subtrees is at most 1.

3. **Binary Tree Representation in C**:
   ```c
   struct Node {
       int data;
       struct Node* left;
       struct Node* right;
   };
   ```

4. **Traversals**:
   - Preorder: Root, Left, Right
   - Inorder: Left, Root, Right
   - Postorder: Left, Right, Root

5. **Applications**:
   - Efficient storage and retrieval of data.
   - Syntax trees for compilers and parsers.
   - Router algorithms.
   - Expression evaluation.

