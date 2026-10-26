# College Algorithms Assignment - Dynamic Programming

Welcome to my repository containing Python implementations of classic algorithms. This project was developed as a college assignment, focusing specifically on design and optimization principles within the **Dynamic Programming** course.

## Author
* **Name:** Toka Mohammed Elalfy Ibrahim Farrag

## Academic Supervision
* **Course:** Dynamic Programming
* **Supervised by:** Dr. Waleed Al-Adrousi
* **Assisted by:** Eng. Sama Ramadan

---

## 📋 Project Summary
This repository contains clean, optimized, and thoroughly tested Python implementations for four fundamental algorithmic problems. The solutions are designed with efficient time and space complexities, handling edge cases and strict validations.

### Included Tasks

#### 1. Nth Fibonacci Number (`FiboNumber`)
* **Approach:** Iterative approach.
* **Time Complexity:** $O(n)$
* **Space Complexity:** $O(1)$ (Optimized to use only constant memory).
* **Description:** Calculates the Nth number in the Fibonacci sequence efficiently without the overhead of recursion.

#### 2. 0/1 Knapsack Problem (`Knapsack`)
* **Approach:** Dynamic Programming (Optimized 1-D Array Tabulation).
* **Time Complexity:** $O(n \times \text{capacity})$
* **Space Complexity:** $O(\text{capacity})$ (Space optimized using the rolling array trick).
* **Description:** Maximizes the total value of items placed in a knapsack without exceeding its maximum weight capacity.

#### 3. Longest Common Subsequence - LCS (`LCS`)
* **Approach:** Dynamic Programming (Bottom-up Tabulation).
* **Time Complexity:** $O(m \times n)$
* **Space Complexity:** $O(m \times n)$
* **Description:** Finds and reconstructs the actual longest common subsequence string between two given sequences.

#### 4. Coin Change Problem (`Coin`)
* **Approach:** Dynamic Programming (Bottom-up Tabulation).
* **Time Complexity:** $O(\text{amount} \times \text{len(coins)})$
* **Space Complexity:** $O(\text{amount})$ (Uses a single 1-D array for space efficiency).
* **Description:** Finds the minimum number of coins needed to make up a given target amount from an unlimited supply of given denominations.

---

## 🚀 How to Run

Make sure you have Python installed, then you can execute any script directly from your terminal:

```bash
# Run Fibonacci script
python FiboNumber

# Run Knapsack script
python Knapsack

# Run LCS script
python LCS

# Run Coin Change script
python Coin
```

All files include automated `assert` sanity checks in their `__main__` blocks to ensure correct functionality upon execution.
