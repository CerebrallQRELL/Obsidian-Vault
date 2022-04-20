### How to Create a Python Dictionary
```Python
new_dict = {  
	“brand”: “Honda”,  
	“model”: “Civic”,  
	“year”: 1995  
}  
print(new_dict)
```

### How to Access a Value in a Dictionary
```Python
x = new_dict[“brand”]
```

Change Item Value
```Python
#Change the “year” to 2020:  
new_dict= {  
	“brand”: “Honda”,  
	“model”: “Civic”,  
	“year”: 1995  
}  
new_dict[“year”] = 2020
```

### Loop Through the Dictionary

```Python
#print all key names in the dictionary  
for x in new_dict:  
	print(x)  
#print all values in the dictionary  
for x in new_dict:  
	print(new_dict[x])  
#loop through both keys and values  
for x, y in my_dict.items():  
	print(x, y)
```

[[Python]]