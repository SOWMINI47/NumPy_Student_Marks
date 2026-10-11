# NumPy Student Marks Analysis

A Python-based project that uses NumPy to perform statistical analysis on student marks. This project calculates the mean, median, maximum, minimum, and standard deviation of a given dataset.

## Project Overview

The NumPy Student Marks Analysis project demonstrates how numerical data can be processed efficiently using Python and the NumPy library. It provides basic statistical insights into student performance using a manually created dataset.

## Objective

- To create a NumPy array containing student marks.
- To calculate the mean and median of the marks.
- To identify the maximum and minimum marks.
- To calculate the standard deviation.
- To understand the application of NumPy in numerical analysis.

## Technologies Used

- **Programming Language:** Python
- **Library:** NumPy
- **Platform:** Google Colab
- **Notebook:** Jupyter Notebook

## Dataset

The project uses a manually created dataset containing marks for 10 students.

```python
marks = np.array([85, 90, 78, 92, 88, 76, 95, 80, 89, 84])
```

## Python Functions Used

| Function | Description |
|---|---|
| `np.array()` | Creates a NumPy array |
| `np.mean()` | Calculates the average marks |
| `np.median()` | Calculates the median value |
| `np.max()` | Finds the highest mark |
| `np.min()` | Finds the lowest mark |
| `np.std()` | Calculates the standard deviation |
| `print()` | Displays the results |

## Implementation

The program performs the following steps:

1. Imports the NumPy library.
2. Creates an array containing student marks.
3. Calculates the mean and median.
4. Finds the maximum and minimum marks.
5. Calculates the standard deviation.
6. Displays the statistical results.

## Results

| Statistical Measure | Result |
|---|---:|
| Mean | 85.7 |
| Median | 86.5 |
| Maximum Marks | 95 |
| Minimum Marks | 76 |
| Standard Deviation | 5.92 |

The results are calculated using NumPy's built-in statistical functions.

## How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook or upload the project notebook.
3. Ensure NumPy is imported using `import numpy as np`.
4. Run all the code cells.
5. View the calculated statistical results.

## Project Structure

```text
NumPy-Student-Marks/
│
├── NumPy_Student_Marks.ipynb
└── README.md
```

- `NumPy_Student_Marks.ipynb` – Contains the Python code and execution results.
- `README.md` – Provides project documentation, implementation details, and results.

## Learning Outcomes

Through this project, I learned:

- How to create and work with NumPy arrays.
- How to perform statistical calculations using NumPy.
- How to calculate mean, median, maximum, and minimum values.
- How to understand standard deviation as a measure of data variation.
- How to analyze numerical data using Python.
- How to organize and document a project on GitHub.

## Conclusion

This project demonstrates the use of NumPy for basic statistical analysis of student marks. It helped me strengthen my understanding of numerical arrays, statistical functions, and data analysis using Python.
