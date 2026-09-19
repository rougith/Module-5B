## NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

x = np.array([1, 5, 3, 8, 6])
y = np.array([2, 5, 1, 7, 9])

indices = np.where(x >= y)

print("Indices where x >= y:")
print(indices)
```

## Output
<img width="1211" height="292" alt="image" src="https://github.com/user-attachments/assets/32cf88c2-33e8-410a-8582-39e9ed0782c6" />


## Result
Hence the code is executd and verified.
