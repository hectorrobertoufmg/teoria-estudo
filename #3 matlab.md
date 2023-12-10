Certainly! Here are your annotations organized using Markdown:


## MATLAB Keywords and Operations

### Referencing the Last Element
You can use the MATLAB keyword `end` as either a row or column index to reference the last element:
```matlab
y = A(end, 2)
```

### Arithmetic with `end`
You can use arithmetic with the keyword `end`. For example:
```matlab
y = A(end-1, end-2)
```

### Matrix Multiplication
The `*` operator performs matrix multiplication. Using it on equally sized vectors results in an error due to incompatible dimensions:
```matlab
z = [3 4] * [10 20]
% Error using  * 
% Incorrect dimensions for matrix multiplication.
```

### Element-Wise Multiplication
The `.*` operator performs element-wise multiplication:
```matlab
z = [3 4] .* [10 20]
z = 
    30    80
```

### Using `size` Function
You can request two output variables from the `size` function:
```matlab
[xrow, xcol] = size(x)
```

### Finding Maximum Value and Index
Use the `max` function to find the maximum value and its corresponding index:
```matlab
[xMax, idx] = max(x)
```

### Ignoring Output with Tilde (~)
If you need only the second output from a function, use a tilde (~) in its place. For example, to get the number of columns in a matrix:
```matlab
[~, xcol] = size(x)
```

### Plotting Multiple Lines on the Same Axes
You can plot one line on top of another in the same axes using the `hold on` command:
```matlab
plot(x1, y1)
hold on
plot(x2, y2)
```

### Task: Plotting with `hold on`
Enter the `hold on` command and plot `mass1` (y-axis) against `sample` (x-axis) with black (k) square (s) markers and no line.

### Plotting a Vector
When you plot a single vector by itself, MATLAB uses the vector values as the y-axis data and sets the x-axis data to the range of 1 to n:
```matlab
plot(y)
```

### Task: Plotting Vector v1
Plot the vector `v1`.

### Setting Line Properties
When using the `plot` function, you can set properties using name-value arguments. For example, to plot with a heavy line:
```matlab
plot(y, 'LineWidth', 5)
```

### Task: Plotting with Line Width
Plot `v1` with a line width of 3.
```matlab
plot(v1, 'LineWidth', 3)
```

You can learn more about available properties in the [Line Properties documentation](https://www.mathworks.com/help/matlab/ref/matlab.graphics.chart.primitive.line-properties.html).
```

Feel free to adjust the formatting as needed.
