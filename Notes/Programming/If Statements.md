### If Statement
```Python
if 5 > 1:  
	print(“That’s True!”)
```

### Nested If Statements
```Python
x = 35  
if x > 20:  
	print(“Above twenty,”)  
	if x > 30:  
		print(“and also above 30!”)
```

### Elif Statements
keyword prompts your program to try another condition if the previous one(s)  was not true
```Python
a = 45  
b = 45  
if b > a:  
	print(“b is greater than a”)  
elif a == b:  
	print(“a and b are equal”)
```

### If Else Statements
```Python
if age < 4:  
ticket_price = 0  
elif age < 18:  
ticket_price = 10  
else: ticket_price = 15
```

If-Not-Statements
```Python
new_list = [1, 2, 3, 4]  
x = 10  
if x not in new_list:  
	print(“’x’ isn’t on the list, so this is True!”)
```

Pass Statements
```Python
a = 33  
b = 200  

if b > a:  
	pass
```

[[Python]]