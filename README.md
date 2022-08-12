# Lowest-Common-Ancestor-of-a-Binary-Search-Tree
Given a binary search tree (BST), find the lowest common ancestor (LCA) node of two given nodes in the BST.
According to the definition of LCA on Wikipedia: “The lowest common ancestor is defined between two nodes p and q as the lowest node in T that has both p and q as descendants (where we allow a node to be a descendant of itself).”

 https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/
 
 ![image](https://user-images.githubusercontent.com/109743699/184274861-4f4f8120-85bc-4660-a79f-b14d8bc8f0c8.png)

Input: root = [6,2,8,0,4,7,9,null,null,3,5], p = 2, q = 8

Output: 6

Explanation: The LCA of nodes 2 and 8 is 6.

Constraints:

The number of nodes in the tree is in the range [2, 105].
-109 <= Node.val <= 109.
All Node.val are unique.
p != q.
p and q will exist in the BST.
