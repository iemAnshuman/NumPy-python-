# Basics of Numpy 
<br>

### Advantages of using numpy
: It helps to create and work with arrays

#### Import
```py
import numpy as np
```

## Creation
```py
a = np.array([1,2,3])
print(a)
```
### arange
to return a range

#### arange(start, end, increment) 
```py
b = np.arange(1,10,2)
```
#### arange(number of integers), start value is 0
```py
c = np.arange(3)
```

### linspace
prints a certain number of int of a range with even space between each num

### linspace(start, end, num of int, data type)
```py
spaced = np.linspace(1,100,5,dtype=int)
#default data type is float 
```

### linspace(start,end,num of int)

## More on Numpy arrays
#### A simple example
```py
char_arr = np.array(['This is numpy'])
print (char_arr)
print (char_arr.dtype) #prints the data type of an array
```

#### np.ones(n)
returns the arr of size n, with all ones as its value
```py
arr = np.one(3)
print(arr)
#output: [1. 1. 1.]
```

#### np.zeros(n)
returns the arr of size n, with all zeros as its value

#### np.empty(n)
returns a new arr of size n, without initializing its entries

