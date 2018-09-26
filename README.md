# Lagrange-interpolating-polynomials
This script will return the lagrange polynomial equation that pases through every points given.
It will draw a graph too.

### Lib required
* Sympy
* Numpy
* Matplotlib

`pip install sympy numpy matplotlib`

## Usage example:
```
$python lagrange-interp.py
Enter every points in this format : x y
Stop the list by entering 0
>Enter point coord: 1 2
>Enter point coord: 2 4
>Enter point coord: 3 7
>Enter point coord: 5 13
>Enter point coord: 0
[[1, 2], [2, 4], [3, 7], [5, 13]]
2*(-X + 2)*(-X/2 + 3/2)*(-X/4 + 5/4) + 4*(-X + 3)*(-X/3 + 5/3)*(X - 1) + 7*(-X/2 + 5/2)*(X/2 - 1/2)*(X - 2) + 13*(X/4 - 1/4)*(X/3 - 2/3)*(X/2 - 3/2)
```

![graph](/Screenshot.png?raw=true "Result Graph")
