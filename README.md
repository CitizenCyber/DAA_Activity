
# Merge Sort Visualization – Divide and Conquer

## Overview
This project is an interactive **Merge Sort Visualization Web Page** built using **HTML, CSS, and JavaScript**.  
It demonstrates the **Divide and Conquer algorithm – Merge Sort** through step-by-step animations and visual explanations.

The visualizer helps users understand how Merge Sort works by displaying the array as bars and animating the sorting process.

---

# Features

### 1. Interactive Visualization
- Array elements are represented as **vertical bars**.
- Bars update dynamically during sorting.
- Visual animation shows how elements are merged step-by-step.

### 2. Step-by-Step Algorithm Animation
Users can control the visualization using:

- **Generate Array** – creates a new random array
- **Play** – runs the Merge Sort animation
- **Pause** – stops the animation
- **Step** – executes one step at a time

### 3. Speed Control
A **slider** allows users to adjust the animation speed.

### 4. Recursion Tree Display
The program displays a **recursion tree** that shows how the array is divided during the divide phase of Merge Sort.

### 5. Algorithm Explanation
The page clearly explains the three stages of Divide and Conquer:

#### Divide
The array is split into two halves repeatedly until each subarray contains only one element.

#### Conquer
Each subarray is sorted recursively. A single element array is already sorted.

#### Combine
The sorted subarrays are merged to produce the final sorted array.

---

# Time Complexity Analysis

## Recurrence Relation
Merge Sort follows the recurrence:

T(n) = 2T(n/2) + O(n)

Where:
- **2T(n/2)** represents sorting the two halves
- **O(n)** represents merging the two halves

## Master Theorem
Using the Master Theorem:

T(n) = O(n log n)

## Complexity Cases

| Case | Time Complexity |
|-----|-----------------|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n log n) |

## Space Complexity
Merge Sort requires additional space for merging:

Space Complexity = **O(n)**

---

# Technologies Used

- **HTML** – Page structure
- **CSS** – User interface and styling
- **JavaScript** – Sorting logic and animation

---

# How to Run the Project

1. Download the project files.
2. Open the file:

merge_sort_visualizer.html

3. Run it in any modern browser such as:
- Google Chrome
- Microsoft Edge
- Firefox
- Safari

4. Use the controls to visualize the Merge Sort process.

---

# Educational Purpose

This visualization is designed for:

- Data Structures and Algorithms learning
- Understanding Divide and Conquer techniques
- Classroom demonstrations
- Algorithm analysis practice

---

# Possible Future Improvements

- Animated recursion tree
- Comparison counter
- Merge operation highlighting
- Support for multiple sorting algorithms
- Mobile responsive interface

---

# Author

Created as part of an **Algorithm Visualization Project** for understanding **Merge Sort and Divide & Conquer techniques**.
