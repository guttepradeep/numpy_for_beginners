# numpy_for_beginners
# NumPy
>--Core library for Scientific computing in Python
>--Central object: "Numpy Array"

What is a NumPy Array?
High-Performance multidimensional array object
Designed specifically for mathematical operations

Types of Arrays
>--1D: Only rows (Axis=0), like a single row.
>--2D: Two axes (row, column).
>--3D: Three axes (row, column, axis).

# Operations and Use Cases with NumPy
Checking NumPy version: np.__version__
Creating an Array: np.array([1, 2, 3, 4, 5, 6, 7, 8])
Checking shape: a.shape
Checking data types of elements: a.dtype
Array Dimensions:
Number of dimensions: a.ndim
Size of the array: a.size
Size in bytes of each element: a.itemsize


# Essential Methods
Element-wise mathematical operations: b = a * np.array([2, 0, 2])
Vector operations: a.dot(b), a @ b, (a * b).sum()


# Array vs List
Appending an item:
List: l.append(10)
Array: np.append(d, 10)


# Broadcasting and Operations
Broadcasting: Allows arrays with different shapes to perform operations.
Indexing, Slicing, and Fancy Indexing
Indexing: Accessing elements by index.
Slicing: Extracting parts of the array.
Boolean Indexing: Using boolean expressions to index.


Concatenation and Splitting
Concatenation:- Combining arrays along an axis (np.concatenate(), np.vstack(), np.hstack()).
Splitting:- Dividing arrays into smaller ones.


Random Number Generation
Generating arrays: np.random.rand(), np.random.randn(), np.random.randint()

Mathematical Functions
Functions: np.sum(), np.mean(), np.std(), np.var()

Matrix Operations
Matrix multiplication: a.dot(b), np.matmul()

Inverse and determinant: np.linalg.inv(), np.linalg.det()

Additional Functions
Reshaping arrays: np.reshape(), np.resize()
Creating specific arrays: np.zeros(), np.ones(), np.eye()
