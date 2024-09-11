# Binary Search Tree Project

This document outlines the steps to create a Binary Search Tree (BST) from the given array: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

## Steps

1. **Root: 7**
   - The first element becomes the root of the tree.

2. **Add 5:**
   - 5 < 7, so it goes to the left of 7.

3. **Add 1:**
   - 1 < 7, go left
   - 1 < 5, go left of 5

4. **Add 8:**
   - 8 > 7, go right of 7

5. **Add 3:**
   - 3 < 7, go left
   - 3 < 5, go left
   - 3 > 1, go right of 1

6. **Add 6:**
   - 6 < 7, go left
   - 6 > 5, go right of 5

7. **Add 0:**
   - 0 < 7, go left
   - 0 < 5, go left
   - 0 < 1, go left of 1

8. **Add 9:**
   - 9 > 7, go right
   - 9 > 8, go right of 8

9. **Add 4:**
   - 4 < 7, go left
   - 4 < 5, go left
   - 4 > 1, go right
   - 4 > 3, go right of 3

10. **Add 2:**
    - 2 < 7, go left
    - 2 < 5, go left
    - 2 > 1, go right
    - 2 < 3, go left of 3

## Final Binary Search Tree Structure

```
              7
            /   \
           5     8
         /   \     \
        1     6     9
       / \
      0   3
         / \
        2   4
```