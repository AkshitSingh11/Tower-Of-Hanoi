# 🏗️ Tower of Hanoi

A Python project that solves and visualizes the classic **Tower of Hanoi** puzzle using recursion and `matplotlib`. This simulation animates each move of the disks between rods, helping you understand the recursive algorithm in a clear and engaging way.

---

## 📌 Features

- Solves the Tower of Hanoi problem for any number of disks (`NUM_DISKS`)
- Visualizes each move using `matplotlib`
- Customizable animation speed
- Shows step count and compares with theoretical move count (2ⁿ - 1)

---

## 🧠 Algorithm

This project uses the **recursive divide-and-conquer** approach to solve the Tower of Hanoi problem. The algorithm is based on the idea that:

1. Move `n-1` disks from source to auxiliary.
2. Move the `nth` disk from source to destination.
3. Move the `n-1` disks from auxiliary to destination.
