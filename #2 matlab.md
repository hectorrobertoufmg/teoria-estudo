Certainly! Here are your annotations organized using Markdown:

## MATLAB Vector and Matrix Operations

### Creating Column Vectors
When you separate numbers using semicolons, MATLAB creates a column vector (n-by-1):
```matlab
x = [1; 3]
x = 
    1
    3
```

### Creating Evenly Spaced Vectors
An alternative method is to use the colon operator (:) for creating evenly spaced vectors:
```matlab
y = 5:8
y = 
    5    6    7    8
```

### Creating Vectors with linspace
If you know the number of elements you want in a vector, use the `linspace` function:
```matlab
x = linspace(0, 1, 5)
x = 
    0    0.250    0.500    0.750    1.000
```
Note the use of commas (,) to separate inputs to the `linspace` function.

### Transposing Vectors and Matrices
The transpose operator (') converts a row vector to a column vector:
```matlab
x = 1:3
x =
    1    2    3

x = x'
x = 
    1
    2
    3
```

### Generating Matrices of Random Numbers
You can generate matrices of random numbers using the `rand` function:
```matlab
x = rand(2)
x = 
    0.8147    0.1270
    0.9058    0.9134
```

### Displaying Size of Vectors or Matrices
Use `size(matrix)` to show the size of a vector or matrix:
```matlab
size(matrix)
```

Feel free to adjust the formatting as needed.
