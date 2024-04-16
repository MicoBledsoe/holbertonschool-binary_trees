# Holberton School Binary Trees Project

## Overview

This repository contains the Binary Trees project, part of the Holberton School curriculum. The project focuses on implementing and manipulating various types of binary trees—a fundamental data structure in computer science used for organizing data efficiently.

## Definition

A binary tree is a tree data structure where each node has at most two children referred to as the left child and the right child. It is characterized by its ability to facilitate fast lookup, addition, and removal operations, each of which can ideally be performed in logarithmic time.

## Functionality

The functions implemented in this project provide a wide range of operations on binary trees, such as insertion, deletion, checking properties (e.g., if a node is a leaf, if the tree is full), and traversals (e.g., pre-order, in-order, post-order).

### Key Functions

- `binary_tree_node`: Creates a binary tree node.
- `binary_tree_insert_left`: Inserts a node as the left-child of another node.
- `binary_tree_insert_right`: Inserts a node as the right-child of another node.
- `binary_tree_delete`: Removes an entire binary tree, freeing all nodes.
- `binary_tree_is_leaf`: Checks if a node is a leaf.
- `binary_tree_is_root`: Checks if a node is the root of the tree.

## Example Usage

Creating a new node in a binary tree can be done using the `binary_tree_node` function. Here is how you might use this function:

#```c
binary_tree_t *root = binary_tree_node(NULL, 10);
binary_tree_t *left_child = binary_tree_node(root, 5);
binary_tree_t *right_child = binary_tree_node(root, 20);

root->left = left_child;
root->right = right_child;


### Part 4: Collaborators and Additional Information
#```markdown

## Additional Information

This project also includes a comprehensive suite of tests to ensure each function behaves as expected. The binary trees implemented here are utilized in various applications, from parsing expressions to managing databases.

## How to Compile

Code files are compiled this way:
#```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o binary_trees

## Collaborators

- **Mico Bledsoe** - [GitHub Profile](https://github.com/MicoBledsoe)
- **Ricardo Corona** - [GitHub Profile](https://github.com/LW068)
