# Data_Analyzer

A beginner-friendly Python program for creating, manipulating, analyzing, and performing mathematical operations on NumPy arrays.

## Features

### 1. Create NumPy Arrays

The program allows you to create:

* 1D arrays
* 2D arrays
* 3D arrays

You can enter the values manually and specify the required dimensions.

### 2. Indexing and Slicing

The program provides basic array access operations:

* Access elements using an index.
* Extract a portion of an array using slicing.

Indexing is supported for 1D arrays, while slicing can be performed on the stored array.

### 3. Combine and Split Arrays

You can:

* Combine arrays using NumPy concatenation.
* Split an array into multiple parts.
* Check array dimensions and shapes before combining.

The program supports combining 1D and 2D arrays when their dimensions are compatible.

### 4. Mathematical Operations

The program supports:

* Addition
* Subtraction
* Multiplication
* Division
* Dot product
* Matrix multiplication

It also checks array shapes and prevents division by zero.

### 5. Search, Sort, and Filter

You can:

* Search for a specific value.
* Sort an array in ascending order.
* Sort an array in descending order.
* Filter values greater than a given number.

NumPy functions such as `where()` and `sort()` are used for these operations.

### 6. Aggregates and Statistics

The program calculates:

* Sum
* Mean
* Median
* Standard deviation
* Variance
* Minimum
* Maximum
* Percentile
* Correlation

These operations are performed using NumPy statistical functions.

## Technologies Used

* Python
* NumPy

## Requirements

Install NumPy using:

```bash
pip install numpy
```

## How to Run

1. Install Python.
2. Install NumPy.
3. Save the program as a Python file, for example:

```text
numpy_analyzer.py
```

4. Run the program:

```bash
python numpy_analyzer.py
```

5. Choose the type of array you want to create.
6. Select an operation from the main menu.

## Main Menu

```text
Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
```

The program starts by asking the user to create a 1D, 2D, or 3D array.

## Example Array Types

```text
Choose Array Type
1. 1D Array
2. 2D Array
3. 3D Array
```

## Concepts Demonstrated

This project demonstrates important NumPy and Python concepts:

* NumPy arrays
* 1D, 2D, and 3D arrays
* Indexing
* Slicing
* Array reshaping
* Array concatenation
* Array splitting
* Mathematical operations
* Dot product
* Matrix multiplication
* Searching
* Sorting
* Filtering
* Statistical calculations
* Correlation
* Python classes
* Static methods
* Private class attributes
* User input
* Menu-driven programming

## Purpose

This project is designed for beginners who want to learn NumPy through practical examples.

It provides a simple menu-driven interface for creating arrays and performing common array operations, mathematical calculations, and statistical analysis.
