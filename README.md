🧮 NumPy Guide
📌 Introduction

NumPy (Numerical Python) is a powerful Python library used for numerical computations. It provides support for arrays, matrices, and many mathematical functions.

🚀 Features
Fast and efficient multi-dimensional arrays
Mathematical operations (linear algebra, statistics)
Broadcasting support
Integration with other libraries like Pandas, Matplotlib
📦 Installation
pip install numpy
📥 Import NumPy
import numpy as np
🔢 Creating Arrays
import numpy as np

arr = np.array([1, 2, 3, 4])
print(arr)

# 2D Array
arr2 = np.array([[1, 2], [3, 4]])
print(arr2)
➕ Array Operations
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

print("Addition:", a + b)
print("Multiplication:", a * b)
📊 Useful Functions
arr = np.array([10, 20, 30, 40])

print("Sum:", arr.sum())
print("Mean:", arr.mean())
print("Max:", arr.max())
print("Min:", arr.min())
🔄 Reshaping Arrays
arr = np.array([1, 2, 3, 4, 5, 6])
reshaped = arr.reshape(2, 3)

print(reshaped)
📐 Indexing & Slicing
arr = np.array([10, 20, 30, 40, 50])

print(arr[0])      # First element
print(arr[1:4])    # Slice
📈 Random Numbers
rand_arr = np.random.rand(3, 3)
print(rand_arr)
🧠 Why Use NumPy?
Faster than Python lists
Memory efficient
Used in Data Science, Machine Learning, AI
📚 Applications
Data Analysis
Machine Learning
Scientific Computing
Image Processing
🤝 Contributing

Feel free to fork this repo and contribute!

📜 License

This project is open-source and free to use.
