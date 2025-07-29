# DSA-group-assignment



🔍 Sorting and Searching Algorithm Comparison (C++)

This is a C++ project that compares the performance of sorting and searching algorithms. It demonstrates the use of **Quick Sort** and **Merge Sort** for sorting random integers, and uses **Binary Search** and **Exponential Search** for searching a target number. The program also measures execution time in **nanoseconds** using the `<chrono>` library.


🚀 Features

- Generates a random list of integers (user-defined size)
- Sorts using:
  - Quick Sort
  - Merge Sort
- Searches using:
  - Binary Search (on QuickSorted array)
  - Exponential Search (on MergeSorted array)
- Measures and displays execution time for all algorithms
- Clean console output with results and performance metrics


🛠 Technologies

**C++**
Standard Libraries: `vector`, `cstdlib`, `ctime`, `algorithm`, `chrono`, `iostream`



🧪 Sample Output

Enter the number of random integers to generate: 10

Generated numbers: 563 77 220 998 43 10 789 322 654 211

Time taken by QuickSort: 14256 nanoseconds

Array after Quick Sort: 10 43 77 211 220 322 563 654 789 998

Time taken by MergeSort: 15340 nanoseconds

Array after Merge Sort: 10 43 77 211 220 322 563 654 789 998

Enter a number to search: 322

Number found at index 5 using Binary Search

Time taken by Binary Search: 310 nanoseconds

Number found at index 5 using Exponential Search

Time taken by Exponential Search: 427 nanoseconds



📊 Algorithm Complexity

| Algorithm          | Time Complexity (Average) |
| ------------------ | ------------------------- |
| Quick Sort         | O(n log n)                |
| Merge Sort         | O(n log n)                |
| Binary Search      | O(log n)                  |
| Exponential Search | O(log n)                  |


📈 Possible Improvements

* Add support for other sorting/searching algorithms (e.g., Heap Sort, Interpolation Search)
* Graphical visualizer or benchmarking chart
* Accept input via files for large datasets
* Add unit tests and modular structure


👨‍💻 Author
**Welcome Shrestha**

Made using C++ for academic and learning purposes.

