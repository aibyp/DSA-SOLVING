# LeetCode 26 - Remove Duplicates from Sorted Array

### Problem

Given a sorted array, remove duplicates in-place and return the count of unique elements.

### Brute Force Idea

Create a new array/vector and store only unique elements while traversing the original array.

* TC: O(n)
* SC: O(n)

### Optimal Idea

Since the array is sorted, duplicate elements appear next to each other.

Use two pointers:

* One pointer keeps track of the position where the next unique element should be placed.
* Another pointer traverses the array.

Whenever a new unique element is found, place it in the next available position and update the count.

### Dry Run

Array: `[1,1,2,2,3]`

* First `1` is unique.
* Second `1` is duplicate → skip.
* `2` is new → place next.
* Second `2` is duplicate → skip.
* `3` is new → place next.

Final unique elements: `[1,2,3]`

### Pattern Learned

**Two Pointers (Fast & Slow Pointer)**

Useful when:

* Array is sorted.
* Need to remove duplicates.
* Need in-place modification.

### Complexity

* TC: O(n)
* SC: O(1)

### Key Learning

When an array is sorted, duplicates are consecutive. Instead of removing elements, keep rewriting the array with only the valid elements.
