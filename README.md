# Insertion-Selection Sort
## Question 1
**[22,27,16,2,18,6] -> Insertion Sort**

**A: Write the stages of the above sequence according to the sort type.**

- [22, 27, 16, 2, 18, 6] -> The first step starts because the first element is already sorted.  
- [22, 27, 16, 2, 18, 6] -> Since the one to the left of 27 is greater than 22, it does not change places.  
- [16, 22, 27, 2, 18, 6] -> 16 is placed at the beginning because it is smaller than the elements to the left of 22 and 27.  
- [2, 16, 22, 27, 18, 6] -> 2 is placed at the beginning because it is smaller than the elements to its left.  
- [2, 16, 18, 22, 27, 6] -> 18 is placed to the left of 22 because it is larger than the elements to its left.  
- [2, 6, 16, 18, 22, 27] -> 6 is placed at the beginning because it is smaller than the elements to its left.

When the Insertion Sort operation is completed, the array is sorted: [2, 6, 16, 18, 22, 27]

**B: Write the Big-O notation.**
- Big-O notation of Insertion Sort is O(n^2)

**C: Time Complexity: After the array is sorted, which of the following cases does the number 18 fall under?**
- [ ] Worst Case
- [ ] Best Case
- [x] Average Case


## Question 2
**Write the first 4 steps of the sequence [7,3,5,8,2,9,4,15,6] according to Selection Sort.**
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]

# Merge Sort
## Question 1
**16,21,11,8,12,22] -> Merge Sort**

**A: Write the stages of the above sequence according to the sort type.** 

Starting sequence: [16, 21, 11, 8, 12, 22]

1. The array is divided into two.
- Lower left array: [16, 21, 11]
-  Bottom right array: [8, 12, 22]

2. Each subarray is sorted within itself.

- Lower left array: [11, 16, 21]
- Bottom right array: [8, 12, 22]

3. The sorted subarrays are merged.

- Combine: [8, 11, 12, 16, 21, 22]

This way, the array is sorted.

Instead of showing the stages one by one, we can summarize them as follows:

Start: [16, 21, 11, 8, 12, 22]

Division: [16, 21, 11], [8, 12, 22]

Sort: [11, 16, 21], [8, 12, 22]

Merge: [8, 11, 12, 16, 21, 22]

**B: Write the Big-O notation.**

The Big-O representation of Merge Sort is O(n log n).

# Binary Search Tree
## Question 1
**Write the Binary-Search-Tree stages of the sequence [7, 5, 1, 8, 3, 6, 0, 9, 4, 2].**

                             7
                           /   \ 
                          5     8
                        /  \      \
                       1    6      9
                         \        /  
                          3      2
                        /   \      
                       0     4    

- Starting Sequence:[7, 5, 1, 8, 3, 6, 0, 9, 4, 2].

1. 7 is selected as root.

2. To the right of 7 is 8.

3. To the left of 7 is 5.

4. To the left of 5 is 1.

5. To the right of 1 is 3.

6. To the left of 3 is 0.

7. To the right of 3 is 4.

8. 6 is found to the right of 5.

9. 9 is found to the right of 8.

10. To the left of 9 is 2.
