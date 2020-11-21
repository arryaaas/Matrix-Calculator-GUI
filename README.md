# Matrix-Calculator-GUI

Matrix Calculator GUI is a desktop application for calculating addition, subtraction, multiplication, scalar multiplication and determinant of a matrix. This application is made using Python Programming Language.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install numpy.

```bash
pip install numpy
```

## Usage

```python
import numpy as np

matrix_a = np.array([1, 2, 3, 4]).reshape(2, 2)
matrix_b = np.array([5, 6, 7, 8]).reshape(2, 2)

matrix_multiplication = np.dot(matrix_a, matrix_b)
matrix_determinant = np.linalg.det(matrix_a)
```

## Libraries
- [Tkinter](https://docs.python.org/3/library/tkinter.html) is a Python binding to the Tk GUI toolkit. It is the standard Python interface to the Tk GUI toolkit, and is Python's de facto standard GUI. Tkinter is included with standard Linux, Microsoft Windows and Mac OS X installs of Python. The name Tkinter comes from Tk interface.
- [NumPy](https://numpy.org/) is a python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely. NumPy stands for Numerical Python.
- [Time](https://docs.python.org/3/library/time.html), The Python time module provides many ways of representing time in code, such as objects, numbers, and strings. It also provides functionality other than representing time, like waiting during code execution and measuring the efficiency of your code.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Mochammad Arya Salsabila - Aryasalsabila789@gmail.com
