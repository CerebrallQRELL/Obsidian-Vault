### Example Lists 

```Python
my_list = [1, 2, 3]  
my_list2 = [“a”, “b”, “c”]  
my_list3 = [“4”, d, “book”, 5]
```
### Add items to list

```Python
//.append adds to the end of list
beta_list = [“apple”, “banana”, “orange”]  
beta_list.append(“grape”)  
print(beta_list)

//.insert adds at index
beta_list = [“apple”, “banana”, “orange”]  
beta_list.insert(“2 grape”)  
print(beta_list)

```

### How to Remove an Item from a List

```Python
beta_list = [“apple”, “banana”, “orange”]  
beta_list.remove(“apple”)  
print(beta_list)

beta_list = [“apple”, “banana”, “orange”]  
beta_list.pop()  
print(beta_list)

beta_list = [“apple”, “banana”, “orange”]  
del beta_list [1]  
print(beta_list)
```

### Combine Two Lists
```Python
my_list = [1, 2, 3]  
my_list2 = [“a”, “b”, “c”]  
combo_list = my_list + my_list2  
combo_list  
[1, 2, 3, ‘a’, ‘b’, ‘c’]

```

### Create Nested List
```Python
my_nested_list = [my_list, my_list2]  
my_nested_list  
[[1, 2, 3], [‘a’, ‘b’, ‘c’]]

```

### Slice a List
```Python
alpha_list[0:4]  
[2, 23, 34, 67
```
### Change Item Value on Your List
```Python
beta_list = [“apple”, “banana”, “orange”]  
beta_list[1] = “pear”  
print(beta_list)
//Outputs [‘apple’, ‘pear’, ‘cherry’]
```

### Loop Through the List

```Python
for x in range(1,4):  
	beta_list += [‘fruit’]  
	print(beta_list)
```

### Copy a List

```Python
beta_list = [“apple”, “banana”, “orange”]  
beta_list = beta_list.copy()  
print(beta_list)

//Or

beta_list = [“apple”, “banana”, “orange”]  
beta_list = list (beta_list)  
print(beta_list)
```
 
### List Comprehensions
```Python
list_variable = [x for x in iterable]

number_list = [x ** 2 for x in range(10) if x % 2 == 0]  
print(number_list)
```

[[Python]]