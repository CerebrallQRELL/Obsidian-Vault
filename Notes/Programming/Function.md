### How to Create a Function
```Python
def name():
	print(“What’s your name?”)


name() //calls function

```


### Function with parameter
```Python
def add_numbers(x, y, z):  
	a = x + y  
	b = x + z  
	c = y + z  
	print(a, b, c)  
add_numbers(1, 2, 3)
//Output a=3, b=4, c=5

```



### How to pass keyword arguments to a function

```Python
#Define function with parameters
def product_info (product name, price):  
	print(”Product Name: “ + product_name)  
	print(”Price: “ + str(price))  

# Define function with parameters  
product_info(”White T-Shirt: “, 15)  
# Call function with parameters assigned as above  
product_info(productname=”Jeans“, price=45)

//output
Product Name: White T-Shirt  
Price: 15  
Product Name: Jeans  
Price: 45




```


[[Python]]