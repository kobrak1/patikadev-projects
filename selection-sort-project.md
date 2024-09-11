[22,27,16,2,18,6] -> Insertion Sort

Show the steps of this arrat according to Insertion Sort

1. [22,27,16,2,18,6] (initial array)
2. [22,27,16,2,18,6] (22 is already in the begining)
3. [16,22,27,2,18,6]
4. [2,16,22,27,18,6]
5. [2,16,18,22,27,6]
6. [2,6,16,18,22,27]

-- Final Sorted Array: [2,6,16,18,22,27]
-- Big O Notation: O(n²)

Time Complexity For 18:
    Best Case: O(1) This occurs if 18 is already in its correct sorted position.
    Average Case: O(n) On average, we might need to compare and shift about half the elements.
    Worst Case: O(n) This occurs when 18 is the last element to be placed in its correct position.


//

[7,3,5,8,2,9,4,15,6] write 4 steps according to Selection Sort

1. [2,3,5,8,7,9,4,15,6] (2 is the smallest, swapped with 7)
2. [2,3,5,8,7,9,4,15,6] (3 is already in the correct position)
3. [2,3,4,8,7,9,5,15,6] (4 is the next smallest, swapped with 5)
4. [2,3,4,5,7,9,8,15,6] (5 is the next smallest, swapped with 8)