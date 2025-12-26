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
~~~
import numpy as np
x=np.array(eval(input()))
sorted=np.sort(x,axis=0)
print("Given array ")
print("",x,"\n")
print(sorted)
~~~

## Output


<img width="795" height="493" alt="image" src="https://github.com/user-attachments/assets/60d1b09b-4f01-4213-b31f-bd0646cb0617" />


## Result

Thus,the program has been executed successfully.
