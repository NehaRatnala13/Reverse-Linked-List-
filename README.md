# Reverse-Linked-List-
Leetcode Reverse Linked List in Python.
# LeetCode 206: Reverse Linked List

## Description
Given the `head` of a singly linked list, reverse the list, and return *the reversed list*.

### Examples

**Example 1:**
* **Input:** head = [1,2,3,4,5]
* **Output:** [5,4,3,2,1]

**Example 2:**
* **Input:** head = [1,2]
* **Output:** [2,1]

**Example 3:**
* **Input:** head = []
* **Output:** []

### Constraints
* The number of nodes in the list is in the range `[0, 5000]`.
* `-5000 <= Node.val <= 5000`

---

## Solutions

This repository provides both the optimal **Iterative** approach and the **Recursive** approach.

### 1. Iterative Approach (Recommended)
* **Time Complexity:** $\mathcal{O}(N)$ — We traverse the list exactly once.
* **Space Complexity:** $\mathcal{O}(1)$ — In-place pointer manipulation with no additional allocation.

### 2. Recursive Approach
* **Time Complexity:** $\mathcal{O}(N)$ — Visited every node once.
* **Space Complexity:** $\mathcal{O}(N)$ — Due to the implicit call stack up to the depth of the list.

---

## Usage

Ensure you have Python 3.8+ installed. You can import the solution class or run it locally by constructing a custom linked list.

```bash
python solution.py
```
