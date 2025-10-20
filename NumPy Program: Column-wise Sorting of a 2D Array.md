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
import numpy as np

a = np.array(eval(input()))

print("Given array")

print(f" {a}")

print()

b = np.sort(a)

print(b)
## Output
<img width="667" height="486" alt="image" src="https://github.com/user-attachments/assets/4c9863e7-fb23-403c-83d5-3239f92627b5" />

## Result
Thus, the program to sort a 2D NumPy array column-wise was executed successfully.
