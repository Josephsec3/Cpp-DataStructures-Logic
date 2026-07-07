# Algorithmic Problem Solving: Tower Building Optimization

## 📊 Overview
This repository contains an optimized C++ solution for calculating tower structures based on specific block sizes. The algorithm efficiently counts the maximum height of a single tower and the total number of distinct towers that can be built.

## 🚀 Technical Highlights
* **Time Complexity:** $O(N)$ due to efficient tracking with an associative array (`std::unordered_map`).
* **I/O Optimization:** Uses `ios_base::sync_with_stdio(false); cin.tie(nullptr);` to significantly decrease input/output execution time, making it suitable for competitive programming limits.

## 🛠️ How It Works
1. The program reads the total number of blocks ($N$).
2. It processes each block size on the fly, storing counts in a hash map.
3. It outputs two metrics:
   * **Max Height:** The height of the tallest tower.
   * **Total Towers:** The number of unique tower bases.
