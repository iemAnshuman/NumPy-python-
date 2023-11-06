# Array math operations
<br>

```py
arr1 = np.array([1,2,3])
arr2 = np.array([4,5,6])

addition = arr1 + arr2
print (addition)

subtraction = arr2 - arr1
print(subtraction)

multiplication = arr1 * arr2
print(multiplication)
```

## Muliplying vector with a scalar (broadcasting)
-> just like in matrices

#### Broadcasting: 
The term broadcasting refers to how numpy treats arrays with different Dimension during arithmetic operations which lead to certain constraints, the smaller array is broadcast across the larger array so that they have compatible shapes. 

## Indexing and Slicing 

```py
#Indexing
a = ([1,2,3,4])
print(a[1])
```

#### For slicing: array[start:end:step]
default= start is 0, end is length of array - 1, and step is 1

## Stacking
to join two or more arrays, either vertically or horizontally 

1. np.vstack(): stacks vertically
2. np.hstack(): stacks horizontally
3. np.hsplit(): splits an array into several smaller horizontal arrays

```py
a1 = np.array([[1,1], 
               [2,2]])
a2 = np.array([[3,3],
              [4,4]])
print(f'a1:\n{a1}')
print(f'a2:\n{a2}')

v = np.vstack((a1,a2))
print(v)

h = np.hstack((a1,a2))
print(h)

hs = np.hsplit(a1,2)
print(hs)
```