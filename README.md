# Experiment-9
🔹 Introduction to NumPy

NumPy (Numerical Python) is an open-source Python library used for numerical computations and scientific computing. It provides support for large, multi-dimensional arrays and matrices along with a wide range of mathematical functions to operate on them.

✅ Why NumPy?
Faster than Python lists (because it is implemented in C and uses contiguous memory allocation)
Used for mathematical and numerical operations
Acts as the base library for Pandas, SciPy, Scikit-learn, and other data science libraries
Supports vectorized operations (operations performed on entire arrays at once)

🔹 1. Array Creation in NumPy
The main object in NumPy is the ndarray (N-dimensional array).
Declaration:
import numpy as np
Creating Arrays:
np.array([elements]) → Creates 1D array
np.array([[...],[...]]) → Creates 2D array
Example:
a is a 1D array
b is a 2D array (matrix)
NumPy arrays store:
Data
Shape
Data type
Dimension

🔹 2. Array Attributes (Properties)
NumPy provides built-in attributes to examine array structure:
Attribute	Description
ndim	Number of dimensions
size	Total number of elements
shape	Rows and columns
dtype	Data type of elements
Example:
a.ndim → 1 (1D array)
b.ndim → 2 (2D array)
a.shape → (7,)
b.shape → (3,3)
a.dtype → int64
These attributes help understand the internal structure of arrays.

🔹 3. In-Built Array Creation Functions
NumPy provides special functions to create arrays quickly:
1️⃣ np.zeros((rows, columns))
Creates array filled with zeros.
2️⃣ np.ones((rows, columns))
Creates array filled with ones.
3️⃣ np.eye(n)
Creates identity matrix (diagonal elements = 1).
4️⃣ np.arange(start, stop, step)
Creates evenly spaced values within a range.
5️⃣ np.linspace(start, stop, number_of_values)
Creates evenly spaced numbers between start and stop.
These functions are very useful in scientific and mathematical applications.

🔹 4. Arithmetic Operations (Vectorized Operations)
NumPy allows performing operations directly on arrays without loops.
Examples:
b * 2 → Multiplies every element by 2
a + 5 → Adds 5 to every element
This is called vectorization, and it makes NumPy much faster than normal Python loops.

🔹 5. Statistical Functions in NumPy
NumPy provides built-in statistical functions:
Function	Description
np.mean()	Average value
np.median()	Middle value
np.max()	Maximum value
np.min()	Minimum value
np.sum()	Sum of elements
Example Results:
Mean = 93.0
Median = 30.0
Max = 500
Min = 1
Sum = 651
These functions help in quick mathematical and statistical analysis.

🔹 6. Advantages of NumPy
High performance
Memory efficient
Supports multi-dimensional arrays
Powerful mathematical operations
Used in machine learning and data science

✅ Conclusion

NumPy is a powerful and efficient numerical computing library in Python. It provides multi-dimensional arrays, fast vectorized operations, and numerous built-in mathematical functions. Because of its speed, memory efficiency, and advanced functionality, NumPy forms the foundation of many data science and scientific computing libraries.

