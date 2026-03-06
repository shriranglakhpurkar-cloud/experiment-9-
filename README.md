NAME - SHRIRANG ANIL LAKHPURKAR 

CLASS-ENTC B2 

PRN-25070123108

THEORY-# NumPy Array Basics – Theory Notes

## Introduction to NumPy

NumPy (Numerical Python) is a powerful Python library used for numerical computing and working with large multi-dimensional arrays and matrices. It provides many built-in mathematical and statistical functions that make calculations faster and easier compared to standard Python lists.

NumPy is widely used in data science, machine learning, scientific computing, and data analysis.

---

# NumPy Arrays

A NumPy array is a collection of elements of the same data type stored in a structured format. Arrays can be one-dimensional, two-dimensional, or multi-dimensional.

### Types of Arrays

1. **1-Dimensional Array (1D Array)**
   A single list of elements arranged in a single row.

2. **2-Dimensional Array (2D Array)**
   A matrix containing rows and columns.

---

# Array Properties

## 1. Dimension of an Array

The dimension of an array refers to the number of axes it has.

* A **1D array** has one dimension.
* A **2D array** has two dimensions (rows and columns).

The dimension helps determine how the data is structured inside the array.

---

## 2. Shape of an Array

The shape of an array defines the size of the array in terms of rows and columns.

Examples:

* A 1D array with seven elements has the shape `(7,)`.
* A 2D array with two rows and three columns has the shape `(2,3)`.

The shape is important when performing mathematical operations on arrays.

---

## 3. Data Type (dtype)

Every element in a NumPy array has a specific data type. This is known as the **dtype**.

Common data types include:

* Integer
* Float
* Boolean

Using a single data type allows NumPy to perform faster computations.

---

# Built-in Array Creation Functions

## Zeros

The zeros function creates an array filled with zero values.
It is useful for initializing arrays before inserting actual data.

Example concept: Creating a matrix where all values start as zero.

---

## Ones

The ones function creates an array filled entirely with the value one.
It is often used for mathematical operations or testing.

---

## Identity Matrix

An identity matrix is a square matrix where:

* All diagonal elements are **1**
* All other elements are **0**

Identity matrices are commonly used in linear algebra and matrix operations.

---

# Range Based Array Functions

## Arange

The arange function creates an array of evenly spaced values within a given interval.

It works similarly to the Python range function but returns a NumPy array.

It allows specification of:

* Starting value
* Ending value
* Step size

---

## Linspace

The linspace function generates a fixed number of evenly spaced values between two points.

Unlike arange, linspace focuses on the **number of values required** rather than the step size.

This is commonly used in mathematical plotting and scientific calculations.

---

# Array Arithmetic Operations

NumPy allows mathematical operations to be performed directly on arrays.

Examples of operations include:

* Addition
* Multiplication
* Subtraction
* Division

These operations are applied **element-wise**, meaning the operation is performed on each element of the array.

This feature makes NumPy extremely efficient for numerical computations.

---

# Statistical Functions in NumPy

NumPy provides several functions for analyzing data.

## Mean

The mean represents the **average value** of all elements in an array.

Mean = Sum of all elements ÷ Total number of elements.

---

## Median

The median is the **middle value** when all elements in the array are arranged in sorted order.

If the number of elements is even, the median is the average of the two middle values.

---

## Maximum

The maximum function returns the **largest value** present in the array.

---

## Minimum

The minimum function returns the **smallest value** present in the array.

---

## Sum

The sum function calculates the **total of all elements** in the array.

This is useful for data analysis and aggregation.

---

# Advantages of NumPy

* Faster numerical calculations
* Efficient memory usage
* Supports multi-dimensional arrays
* Provides powerful mathematical functions
* Widely used in data science and machine learning

---

# Conclusion

NumPy is an essential Python library for working with numerical data. By using arrays, built-in creation functions, arithmetic operations, and statistical tools, NumPy simplifies complex mathematical and data processing tasks. Understanding array dimensions, shape, and statistical functions is fundamental for anyone learning data analysis or scientific computing in Python.
