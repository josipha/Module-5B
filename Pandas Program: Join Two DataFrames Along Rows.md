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
    'Name': ['Alice', 'Bob'],
    'Age': [20, 21],
    'Grade': ['A', 'B']
}

student_data2 = {
    'Name': ['Charlie', 'David'],
    'Age': [19, 22],
    'Grade': ['A', 'C']
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print(combined_df)
```

## Output

<img width="425" height="287" alt="image" src="https://github.com/user-attachments/assets/7b2b25c9-b1dc-4c01-9771-c679140e5a60" />


## Result

Thus,a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
