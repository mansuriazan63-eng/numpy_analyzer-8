# NumPy Analyzer – Menu-Driven NumPy Toolkit

## 📌 Project Overview

**NumPy Analyzer** is a menu-driven Python application designed to perform various operations on NumPy arrays.

This project demonstrates the use of NumPy functionalities integrated with Object-Oriented Programming (OOP) principles. It allows users to create, manipulate, analyze, combine, split, search, sort, and filter NumPy arrays through an interactive menu.

The project is developed using Python and the NumPy library.

## 🚀 Features

The NumPy Analyzer provides the following features:

### 1. Array Creation

- Create 1D arrays.
- Create 2D arrays.
- Create 3D arrays.
- Enter array elements manually.

### 2. Indexing and Slicing

- Access individual array elements using indexing.
- Extract specific elements using slicing.
- Support for 1D, 2D, and 3D arrays.

### 3. Mathematical Operations

- Addition
- Subtraction
- Multiplication
- Division
- Dot Product
- Matrix Multiplication

### 4. Array Combining and Splitting

- Combine two arrays using Concatenate.
- Combine arrays using Vertical Stack (`vstack`).
- Split arrays into smaller equal parts.

### 5. Search, Sort, and Filter

- Search for a specific value.
- Sort arrays in ascending order.
- Sort arrays in descending order.
- Filter elements using conditions:
  - Greater than (>)
  - Less than (<)
  - Equal to (==)
  - Not equal to (!=)
  - Greater than or equal to (>=)
  - Less than or equal to (<=)

### 6. Aggregates and Statistics

- Sum
- Mean
- Median
- Standard Deviation
- Variance
- Minimum
- Maximum
- Percentile
- Correlation Coefficient

## 🛠️ Technologies Used

- **Python** – Programming Language
- **NumPy** – Numerical Computing Library
- **Object-Oriented Programming (OOP)** – Code Structure and Design

## 📂 Project Structure

```text
NumPy-Analyzer/
│
├── numpy_analyzer.py
│
├── README.md
│
└── requirements.txt
```

## ⚙️ Installation and Setup

Follow these steps to run the project on your computer.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/NumPy-Analyzer.git
```

### Step 2: Navigate to the Project Folder

```bash
cd NumPy-Analyzer
```

### Step 3: Install NumPy

```bash
pip install numpy
```

Alternatively, install dependencies using:

```bash
pip install -r requirements.txt
```

### Step 4: Run the Program

```bash
python numpy_analyzer.py
```

## 💻 Main Menu

When you run the program, the following menu will appear:

```text
=======================================================
       Welcome to the NumPy Analyzer!
=======================================================
Choose an option:

1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit

=======================================================
```

Select an option and follow the instructions displayed on the screen.

## 🧠 OOP Concepts Implemented

This project demonstrates several Object-Oriented Programming concepts:

### 1. Class and Object

The `DataAnalytics` class encapsulates all NumPy operations.

### 2. Constructor (`__init__`)

The constructor initializes the NumPy array and tracks the number of objects created.

### 3. Encapsulation

Private helper methods are used to handle internal operations and validations.

### 4. Class Method (`@classmethod`)

The `get_instance_count()` method returns the total number of objects created.

### 5. Static Method (`@staticmethod`)

The `array_info()` method provides basic information about an array, including its shape, dimensions, size, and data type.

### 6. Private Helper Methods

Methods such as `_ensure_array_exists()` and `_validate_same_shape()` help manage internal operations.

## 🎯 Learning Objectives

Through this project, users can learn:

- How to work with NumPy arrays.
- How to perform mathematical operations using NumPy.
- How to manipulate multidimensional arrays.
- How to apply indexing and slicing.
- How to implement OOP concepts in Python.
- How to use class methods and static methods.
- How to implement encapsulation and input validation.

## 🔮 Future Improvements

Possible future enhancements include:

- Graphical User Interface (GUI).
- Data visualization using Matplotlib.
- Support for CSV and Excel files.
- Advanced statistical analysis.
- Exporting analysis results to files.

## 👨‍💻 Author

**Author:** kaif&#x20;

**Project:** NumPy Analyzer

**Language:** Python

## 📜 License

This project is open for educational and learning purposes.
