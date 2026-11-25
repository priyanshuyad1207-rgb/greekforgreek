# 🔍 Linear Search

[**Linear Search**](https://www.geeksforgeeks.org/problems/search-an-element-in-an-array-1587115621/1)

## 📌 Problem Description

Given an array `arr[]` of integers and an integer `x`, find the index of the first occurrence of `x` in the array.

If the element is not present, return `-1`.

## 💡 Approach

- Traverse the array using a `for` loop.
- Compare each element with the target `x`.
- If `arr[i] == x`, return the current index `i`.
- If the target is not found after traversing the entire array, return `-1`.


## 🧪 Example

**Input:**
```text
arr = [1, 2, 3, 4, 5]
x = 4
```

**Output:**
```text
3
```

**Explanation:**

The element `4` is present at index `3`, so we return `3`.

## ⏱️ Complexity Analysis

- **Time Complexity:** `O(n)` – In the worst case, we traverse the entire array.
- **Space Complexity:** `O(1)` – No extra space is used.

## 🏷️ Topics

- Array
- Linear Search
- Searching

