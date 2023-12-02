# find-even-numbers-from-an-arrey-in-python

# Python code To print all even numbers
# in a given list using numpy array
import numpy as np
 
# Declaring Range
temp = [2, 7, 5, 64, 14]
li = np.array(temp)
 
# printing even numbers using numpy array
even_num = li[li % 2 == 0]
print(even_num)
