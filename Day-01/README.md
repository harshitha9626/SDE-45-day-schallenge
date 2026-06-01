# 🚀 Striver SDE Sheet Challenge

## 📅 Day 01

### ✅ Problems Solved

#### 1. Set Matrix Zeroes

**Problem Statement:**  
Given an `m × n` matrix, if an element is `0`, set its entire row and column to `0`.

**Approach:**
- Use the first row and first column as markers.
- Mark rows and columns that need to be converted to zero.
- Traverse the matrix again and update the values.

**Time Complexity:** `O(m × n)`  
**Space Complexity:** `O(1)`

---

#### 2. Pascal's Triangle

**Problem Statement:**  
Generate the first `numRows` of Pascal's Triangle.

**Approach:**
- Create rows one by one.
- First and last elements of every row are `1`.
- Remaining elements are obtained by summing adjacent elements from the previous row.

**Time Complexity:** `O(n²)`  
**Space Complexity:** `O(n²)`

---

#### 3. Next Permutation

**Problem Statement:**  
Find the lexicographically next greater permutation of the given array.

**Approach:**
- Find the first decreasing element from the right.
- Find the next greater element and swap them.
- Reverse the remaining suffix.

**Time Complexity:** `O(n)`  
**Space Complexity:** `O(1)`

---

## 📊 Progress

| Day | Problems Solved |
|------|----------------|
| Day 01 | Set Matrix Zeroes, Pascal's Triangle, Next Permutation |

### 🎯 Total Problems Solved
**3**

### 💻 Language
**Java**

### ✅ Status
Completed Day 01 Successfully
