# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np

# Original 2D array
arr = np.array([[10, 20, 30],
                [40, 50, 60],
                [70, 80, 90]])

# New column to insert
new_col = np.array([100, 200, 300])

# Delete the second column (index 1)
arr = np.delete(arr, 1, axis=1)

# Insert the new column at index 1
arr = np.insert(arr, 1, new_col, axis=1)

print("Updated Array:")
print(arr)
```

## Output
<img width="1198" height="486" alt="image" src="https://github.com/user-attachments/assets/be99d8c7-1a96-4cc3-8eba-a845cdf0b6db" />


## Result
Hence the code is executed and verified.
