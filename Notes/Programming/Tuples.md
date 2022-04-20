How to Create a Tuple
```Python
my_tuple = (1, 2, 3, 4, 5)  
my_tuple[0:3]  
(1, 2, 3)
```

How to Slide a Tuple
```Python
numbers = (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12)  
print(numbers[1:11:2])

//Output (1,3,5,7,9)
```

Convert Tuple to a List
```Python
x = (“apple”, “orange”, “pear”)  
y = list(x)  
y[1] = “grape”  
x = tuple(y)  
print(x)
```

[[Python]]