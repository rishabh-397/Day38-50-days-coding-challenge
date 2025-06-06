# Day38-50-days-coding-challenge
## 🚀 Overview

Welcome to Day 38 of my #50DaysOfCoding challenge!  
Today, I solved two problems – one based on Binary Search Tree (BST) search and the other on palindrome validation from strings.

---

## 🧩 Problem 1: Search in a Binary Search Tree

### 🔍 Problem Statement
Given the `root` of a Binary Search Tree (BST) and an integer `val`, find the node in the BST that matches the `val` and return the subtree rooted at that node. If such a node does not exist, return `null`.

### ✅ Constraints
- The number of nodes in the tree is in the range [1, 5000].
- `1 <= Node.val <= 10⁷`
- The tree is a valid BST.
- `1 <= val <= 10⁷`

### 🧠 Approach
- Use the **binary search property** of BSTs: left < root < right.
- Traverse recursively or iteratively.
- Stop when `val == node.val` or when reaching a leaf.

### 💡 Sample Input/Output
**Input:** root = [4,2,7,1,3], val = 2  
**Output:** [2,1,3]

---

## 🧩 Problem 2: Valid Palindrome

### 🔍 Problem Statement
Check whether a given string `s` is a palindrome after:
- Converting all uppercase letters into lowercase
- Removing all non-alphanumeric characters

### ✅ Constraints
- `1 <= s.length <= 2 * 10⁵`
- `s` consists only of printable ASCII characters.

### 🧠 Approach
- Filter out non-alphanumeric characters.
- Convert to lowercase.
- Use two-pointer technique from both ends.

### 💡 Sample Input/Output
**Input:** "A man, a plan, a canal: Panama"  
**Output:** `true`  

**Input:** "race a car"  
**Output:** `false`

---

## 🧠 What I Learned Today
- Revisited properties of BST and their efficient traversal
- Implemented string normalization and two-pointer strategy
- Understood performance trade-offs between iterative vs recursive methods
- Applied real-world input validation and cleaning in palindrome checking
