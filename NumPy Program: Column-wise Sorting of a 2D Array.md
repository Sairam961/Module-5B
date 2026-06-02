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
a=np.array([[3,2,1],
            [6,5,4],
            [9,8,7]])
b=np.sort(a,axis=0)
print(a)
print(b)
```

## Output

<img width="1555" height="545" alt="image" src="https://github.com/user-attachments/assets/a807816a-2f99-4817-85e3-0854df1d7ab3" />


## Result
Thus the program has been successfully executed
