[16,21,11,8,12,22] -> Merge Sort

Step 1. Divide the array into two halves
[16,21,11] [8,12,22]

Step 2. Divide the subarrays
[16] [21,11] and [8] [12,22]

Step 3. Divide until each array has a single element
[16] [21] [11] and [8] [12] [22]

Step 4. Start Merging and Sorting
[16] [11,21] and [8] [12,22]

Step 5. Continue Merging and Sorting
[11,16,21] [8,12,22]

Step 6. Final Merge and Sort
[8,11,12,16,21,22]


# Result: [8,11,12,16,21,22]