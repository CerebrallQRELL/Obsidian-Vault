### How to Create a Class
```Python
class TestClass:  
z = 5
```

### How to Create an Object
```Python
p1 = TestClass()  
print(p1.x)

class car(object):  
	“””docstring”””  
def __init__(self, color, doors, tires):  
	“””Constructor”””  
	self.color = color  
	self.doors = doors  
	self.tires = tires 
	 
def brake(self):  
	“””  
	Stop the car  
	“””  
	return “Braking”
	  
def drive(self):  
	“””  
	Drive the car  
	“””  
	return “I’m driving!”

```

### How to Create a Subclass
```Python
class Car(Vehicle):  
	“””  
	The Car class  
	“””
	  
def brake(self):  
	“””  
	Override brake method  
	“”” 	 
return “The car class is breaking slowly!” 

if __name__ == “__main__”:  
	car = Car(“yellow”, 2, 4, “car”)  
	car.brake()  
	‘The car class is breaking slowly!’  
	car.drive()  
	“I’m driving a yellow car!”
```