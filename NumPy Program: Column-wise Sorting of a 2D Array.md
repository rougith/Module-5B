# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

# Create a 2D array
arr = np.array([[9, 4, 7],
                [2, 8, 1],
                [5, 3, 6]])

# Sort each column in ascending order
sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="1090" height="408" alt="image" src="https://github.com/user-attachments/assets/5c831b85-ba5f-47da-871c-f6310b59e52c" />


## Result
Hence the code is executed and verified.

