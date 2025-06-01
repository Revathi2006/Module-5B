
# NumPy Program: Column-wise Sorting of a 2D Array
## NAME : REVATHI.S
## REG NO: 212224230228
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
x=np.array(eval(input()))
sorted=np.sort(x,axis=1)
print("Given array ")
print("",x,"\n")
print(sorted)
```
## Output
![image](https://github.com/user-attachments/assets/bb8f9a2f-0b92-4bd7-9064-1d385f0b8fa9)

## Result
Thus,the program has been executed successfully.

