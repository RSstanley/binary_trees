# C - Binary trees


## About this project:
In this project i learnt and practiced:
- What is a binary tree
- What is the difference between a binary tree and a Binary Search Tree
- What is the possible gain in terms of time complexity compared to linked lists
- What are the depth, the height, the size of a binary tree
- What are the different traversal methods to go through a binary tree
- What is a complete, a full, a perfect, a balanced binary tree

## Tasks file description:

  * [binary_tree_print.c](./binary_tree_print.c): C function that prints binary
  trees in a pretty way.

  * [binary_trees.h](./binary_trees.h): Header file containing definitions and
  prototypes for all types and functions written for the project.

  * [0-binary_tree_node.c](./0-binary_tree_node.c): C function that creates a
  binary tree node with a given parent and value.
  * Returns a pointer to the new node, or `NULL` on failure.

  * [1-binary_tree_insert](./1-binary_tree_insert): C function that inserts a
  node as the left-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a left node, the new node takes its
  place and the old left-child becomes the left-child of the new node.

  * [2-binary_tree_insert_right.c](./2-binary_tree_insert_right.c): C function that
  inserts a node as the right-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a right node, the new node takes its
  place and the old right-child becomes the right-child of the new node.

  * [3-binary_tree_delete.c](./3-binary_tree_delete.c): C function that deletes
  an entire binary tree.

  * [4-binary_tree_is_leaf.c](./4-binary_tree_is_leaf.c): C function that checks
  if a given node is a leaf.
  * Returns `1` if the node is a leaf, `0` otherwise.

  * [5-binary_tree_is_root.c](./5-binary_tree_is_root.c): C function that checks
  if a given node is a root.
  * Returns `1` if the node is a root, `0` otherwise.

  * [6-binary_tree_preorder.c](./6-binary_tree_preorder.c): C function that
  traverses a tree using pre-order traversal.

  * [7-binary_tree_inorder.c](./7-binary_tree_inorder.c): C function that
  traverses a tree using in-order traversal.

  * [8-binary_tree_postorder.c](./8-binary_tree_postorder.c): C function that
  traverses a tree using post-order traversal.

  * [9-binary_tree_height.c](./9-binary_tree_height.c): C function that returns
  the height of a binary tree.

  * [10-binary_tree_depth.c](./10-binary_tree_depth.c): C function that returns
  the depth of a given node in a binary tree.

  * [11-binary_tree_size.c](./11-binary_tree_size.c): C function that returns
  the size of a binary tree.

  * [12-binary_tree_leaves.c](./12-binary_tree_leaves.c): C function that returns
  the number of leaves in a binary tree.

  * [13-binary_tree_nodes.c](./13-binary_tree_nodes.c): C function that returns
  the number of nodes in a binary tree with at least one child.

  * [14-binary_tree_balance.c](./14-binary_tree_balance.c): C function that
  returns the balance factor of a binary tree.

  * [15-binary_tree_is_full.c](./15-binary_tree_is_full.c): C function that
  checks if a binary tree is full.
  * Returns `1` if a tree is full, `0` otherwise.

  * [16-binary_tree_is_perfect.c](./16-binary_tree_is_perfect.c): C function
  that checks if a binary tree is perfect.
  * Returns `1` if a tree is perfect, `0` otherwise.

  * [17-binary_tree_sibling.c](./17-binary_tree_sibling.c): C function that
  returns a pointer to the sibling of a given node in a binary tree.
  * Returns `NULL` if no sibling is found.

  * [18-binary_tree_uncle.c](./18-binary_tree_uncle.c): C function that
  returns a pointer to the uncle of a given node in a binary tree.
  * Returns `NULL` if no uncle is found.

  * [100-binary_trees_ancestor.c](./100-binary_trees_ancestor.c): C function
  that returns a pointer to the lowest common ancestor node of two given nodes
  in a binary tree.
  * Returns `NULL` if no common ancestor is found.

  * [101-binary_tree_levelorder.c](./101-binary_tree_levelorder.c): C function
  that traverses a binary tree using level-order traversal.

  * [102-binary_tree_is_complete.c](./102-binary_tree_is_complete.c): C function
  that checks if a binary tree is complete.
  * Returns `1` if the tree is complete, `0` otherwise.

  * [103-binary_tree_rotate_left.c](./103-binary_tree_rotate_left.c): C function
  that performs a left-rotation on a binary tree.
  * Returns a pointer to the new root node of the tree after rotation.

  * [104-binary_tree_rotate_right.c](./104-binary_tree_rotate_right.c): C function
  that performs a right-rotation on a binary tree.
  * Returns a pointer to the new root node of the tree after rotation.

  * [110-binary_tree_is_bst.c](./110-binary_tree_is_bst.c): C function that
  checks if a binary tree is a valid binary search tree.
  * Returns `1` if the tree is a valid BST, `0` otherwise.

  * [111-bst_insert.c](./111-bst_insert.c): C function that inserts a value into
  a binary search tree.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the tree is `NULL`, the value becomes the root node.
  * The value is ignored if it is already present in the tree.

  * [112-array_to_bst.c](./112-array_to_bst.c): C function that builds a binary
  search tree from an array.
  * Returns a pointer to the root node of the created tree, or `NULL` on failure.

  * [113-bst_search.c](./113-bst_search.c): C function that searches for a value
  in a binary search tree.
  * If the value is matched in the BST, returns a pointer to the matched node.
  * Otherwise, returns `NULL`.

  * [114-bst_remove.c](./114-bst_remove.c): C function that removes a node from
  a binary search tree.
  * Returns a pointer to the new root node of the tree after deletion.
  * If the node to be deleted has two children, it is replaced with its first
  in-order successor.

  * [115-O](./115-O): Text file containing the average time complexities of
  binary search tree operations (one answer per line):
    * Inserting the value `n`.
    * Removing the node with the value `n`.
    * Searching for a node in a BST of size `n`.

  * [120-binary_tree_is_avl.c](./120-binary_tree_is_avl.c): C function that checks if
  a binary tree is a valid AVL tree.
  * If the tree is a valid AVL tree, returns `1`.
  * Otherwise, returns `0`.

  * [121-avl_insert.c](./121-avl_insert.c): C function that inserts a value in an AVL tree.
  * Returns a value to the inserted node, or `NULL` on failure.

  * [122-array_to_avl.c](./122-array_to_avl.c): C function that builds an AVL tree
  from an array.
  * Returns a pointer to the root node of the created AVL tree, or `NULL` on failure.
  * Ignores duplicate values.

  * [125-O](./125-O): Text file containing the average time complexities of AVL tree
  opeartions (one answer per line):
    * Inserting the value `n`.
    * Removing the node with the value `n`.
    * Searching for a node in an AVL tree of size `n`.

  * [135-O](./135-O): Text file containing the average time complexities of
  binary heap opeartions (one answer per line):
    * Inserting the value `n`.
    * Extracting the root node.
    * Searching for a node in a binary heap of size `n`