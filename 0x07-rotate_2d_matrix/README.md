## 0x07. Rotate 2D Matrix

For the “0. Rotate 2D Matrix” project, you are tasked with implementing an in-place algorithm to rotate an n x n 2D matrix by 90 degrees clockwise. This challenge requires a good understanding of matrix manipulation and in-place operations in Python. Below are the key concepts and resources that you need to grasp in order to successfully complete this project.

## Concepts Needed:
1. **Matrix Representation in Python:**

- Understanding how 2D matrices are represented using lists of lists in Python.
- Accessing and modifying elements in a 2D matrix.

2. **In-place Operations:**
- Performing operations on data without creating a copy of the data structure.
- The importance of minimizing space complexity by modifying the matrix in place.

3. **Matrix Transposition:**
- Understanding the concept of transposing a matrix (swapping rows and columns).
- Implementing matrix transposition as a step in the rotation process.

4. **Reversing Rows in a Matrix:**
- Manipulating rows of a matrix by reversing their order as part of the rotation process.

5. **Nested Loops:**
- Using nested loops to iterate through 2D data structures like matrices.
- Modifying elements within nested loops to achieve the desired rotation.

## Resources:

- Python Official Documentation:
- [Data Structures (list comprehensions, nested list comprehension)](# "https://docs.python.org/3/tutorial/datastructures.html")

- [More on Lists](# "https://www.geeksforgeeks.org/transpose-matrix-single-line-python/")

- GeeksforGeeks Articles:
[Inplace rotate square matrix by 90 degrees](# "https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/")
[Transpose a matrix in Single line in Python
TutorialsPoint:](# "https://docs.python.org/3/tutorial/datastructures.html#more-on-lists")

[Python Lists](# "https://www.tutorialspoint.com/python/python_lists.htm")
 for basics of list manipulation in Python.

By understanding these concepts and utilizing the provided resources, you will be able to approach the problem methodically, first transposing the matrix and then reversing each row to achieve a 90-degree clockwise rotation. This project not only tests your ability to manipulate 2D matrices but also challenges you to think about optimizing your solution to operate in-place, thus improving their problem-solving and algorithmic thinking skills in Python.

## Additional Resources

[Mock Technical Interview](# "https://www.youtube.com/watch?feature=shared&v=yM9Xbi-MigE")

## Tasks To Complete
+ [x] 0. **Rotate 2D Matrix**<br/>[0-rotate_2d_matrix.py](0-rotate_2d_matrix.py) contains a module with a function that rotates an `n` x `n` 2D matrix 90 degrees clockwise with the following requirements:
  + Prototype: `def rotate_2d_matrix(matrix):`.
  + Do not return anything. The matrix must be edited **in-place**.
  + You can assume the matrix will have 2 dimensions and will not be empty.
