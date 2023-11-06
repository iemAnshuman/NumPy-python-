# Multi dimensional array
<br>

## creation
```py
arr = np.array([[1,2,3], [4,5,6]])
print(arr)
```

#### np.reshape(arr, (m,n))
where m and n are dimensions of arr

## finding shape, size and dimension
1. arr.ndim: returns the number of dimensions of the array
2. arr.shape: returns the shape of the array
3. arr.size: stores the number of elements in the array

```py
arr = np.array([[1,2,3], [4,5,6]])
print(arr.ndim) #out: 2
print(arr.shape) #out: (2,3)
print(arr.size) #out: 6
```


