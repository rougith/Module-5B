# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

student_data1 = {
    'Student_ID': [1, 2, 3],
    'Name': ['John', 'Alice', 'Bob'],
    'Marks': [85, 90, 78]
}

student_data2 = {
    'Student_ID': [4, 5, 6],
    'Name': ['David', 'Eva', 'Frank'],
    'Marks': [88, 92, 80]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

new_df = pd.concat([df1, df2], axis=0)

print(new_df)
```
## Output
<img width="1146" height="478" alt="image" src="https://github.com/user-attachments/assets/55e79242-2dd0-4d0a-b9ae-3460de0add58" />


## Result
Hence the code is executed and verified.
