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

elements = list(map(int, input("Enter elements separated by space: ").split()))
arr = np.array(elements).reshape(3, 4)
sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)
print("Column-wise Sorted Array:")
print(sorted_arr)

```

## Output
<img width="807" height="376" alt="image" src="https://github.com/user-attachments/assets/96fe9007-f737-4aa2-8c7c-946c87a9306d" />


## Result

Thus,a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
