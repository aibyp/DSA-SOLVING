# Two Sum

## Pattern

Arrays

---

## Problem Link

https://leetcode.com/problems/two-sum/

---

## Problem Statement

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

---

## My Initial Thought

Since I was just starting with arrays, my first idea was to compare every possible pair.

---

## Approach

1. Traverse array using first loop.
2. Traverse remaining elements using second loop.
3. Check if sum equals target.
4. Return indices.

---

## Dry Run

nums = [2,7,11,15]

target = 9

2 + 7 = 9

Answer = [0,1]

---

## Complexity Analysis

Time Complexity: O(n²)

Space Complexity: O(1)

---

## Learning

This problem taught me how brute force works and why optimization using hashing is needed.
