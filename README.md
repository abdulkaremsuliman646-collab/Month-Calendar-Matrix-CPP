# 🗓️ C++ Monthly Calendar Generator (Grid Matrix)

A clean, modular C++ application designed to compute and display a perfectly aligned monthly calendar in the console for any Gregorian calendar date.

## 🚀 Key Engineering Concepts
- **Congruence Day-of-Week Algorithm:** Calculates exact weekday offsets ($O(1)$) to determine the starting column index for day 1.
- **Dynamic Leap Year Resolution:** Computes February boundaries based on full century and leap year rules.
- **Fixed-Width Column Formatting:** Utilizes formatted specifiers (`%5d`) to ensure rigid vertical alignment across irregular month boundaries.
- **State-Tracking Grid Iteration:** Employs modular counters to handle row-wrapping seamlessly upon reaching the 7-day boundary.

## 🛠️ Tech Stack
- **Language:** C++
- **Paradigms:** Modular Programming, Algorithmic Time Formatting
