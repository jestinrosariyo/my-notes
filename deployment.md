# Python Basics

**What is Python?**

Python is a high level, interpreted and Object Oriented Programming Language.

**Why High Level?**

It allows you to write instructions in a easy to understand format, rather than complex machine code.

**Why Interpreted?**

Python doesn’t need to be compiled before running, It executes line by line using an interpreted.

**OOPs:**

**Ex:**

Object → It is real world entity contain State, behaviors. 

State → Represent as instance variables or attributes.

Behavior → Represent by methods or functions.

Class → Class is a blueprint.

Constructor → It will be called at the time of creating an object.

**Syntax:**

```python
class Dog:
	def __init__ (self,name,breed)
	    self.name=name
	    self.breed=breed
	def bark(self):
			print(f"{self.name} is barking")
	def info(self):
			print(f"{self.name} is {self.breed})
d1=Dog("Bruno","Labrador")
d1.bark()
d1.info()
```

**o/p:**

Bruno is barking

Bruno is Labrador

**Explanation:**

class =Dog

def is an function

init is a constructor

self refers current class object

f → format
