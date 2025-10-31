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

arr = np.array(list(map(int, input("Enter 12 elements of 3x4 array: ").split()))).reshape(3, 4)
new_col = np.array(list(map(int, input("Enter 3 elements of new column: ").split())))

arr = np.delete(arr, 1, axis=1)
arr = np.insert(arr, 1, new_col, axis=1)

print("Updated Array:")
print(arr)
```

## Output

<img width="822" height="297" alt="image" src="https://github.com/user-attachments/assets/095e610a-948e-4f27-85d1-f992cb0f8883" />

## Result

Thus,a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is executed successfully.

