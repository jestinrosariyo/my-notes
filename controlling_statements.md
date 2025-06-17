# Controlling Statements and Boolean values

      In Python we have 3 types of controlling statements.

  1. Conditional statements / Decision Making statements.
  2. Looping statements / Iterative statements.
  3. Transfer / Jump statements.

### **Conditional statements:**

      Conditional statements help a program make decision based on condition.

**Types of Conditional statements:**

  1. if statements.
  2. if…else statements.
  3. if…elif….else statements.
  4. Nested if statements.

**1. if statements:**

  Used when you want to check a single condition.

**Syntax:**
  ```python
  age=20
  if age >= 18:
	  print("You are eligiable to vote")
  ```

**2.if…else statements:**

  Used to choose between two paths.

**Syntax:**
  ```python
  if num%2 == 0
	  print("Even Number")
  else:
	  print("Odd Number")
  ```

**3.if…elif….else statements:**

  Used when you have multiple conditions to check.

**Syntax:**
  ```python
  mark=77
  if mark >=90
	  print("Excellent")
  elif mark >=70
	  print("Good")
  elif mark >=50
	  print("Okay")
  else:
	  print("Need Improvement")
  ```

**4.Nested if statements:**

  An if inside another if used for checking sub-conditions.

**Syntax:**
  ```python
  age=28
  country="India"
  if age >18 and country == "India"
	  print("You can apply for Driving Lincence")
  ```

  if block or else block ,any of the one only work according to the condition.

  In Python, a **Boolean** represents one of two values: `True` or `False`. Booleans are commonly used in conditional statements, logical operations and control flow.

**Comparison Operator:**

  Which is used to compare two variables.(==)This is one of the Comparison operator.

**Syntax:**
  ```python
  rcb="win"
  if (rcb=="win"):
    print("Win")
  else:
    print("Loss")
  ```

**o\p:**

win

 **Ex:**
  ```python
  navi="success"
  if (navi=="success"):
      print("Good Life")
  else:
      print("Bad Life")
  ```

**o\p:**

  Good Life

### **Looping statements:**

     Generating sequence of number is called range function.

**Syntax:**

  range(start value , end value , step value)

  step value → end value -1  #Increment

  step value → end value +1 #Decrement

  start value and step value is optional

  start value default value is 0

  step value default value is 1(Positive values)

  end value is must required

**Ex:**
  ```python
	  range(10)    # (0,10,1)
		  [0,1,2,3,4,5,6,7,8,9]
	  range(3,10)  # (3,10,1)
		  [3,4,5,6,7,8,9]
	  range(3,10,2) # (3,10,2)
		  [3,5,7,9]
	  range(10,1,2) # for reverce loop that won't work
	
	  range(10,1,-1) # correct way to reverce loop
		  [10,9,8,7,6,5,4,3,2]
  ```

**We have two types of loop:**

  1. for loop
  2. while loop

**1)For Loop:**

  Python For Loops are used for iterating over a sequence like lists, tuples, strings, and ranges.

**Syntax:**

  for variable name in sequence object

  it is a group of values (list, set, tuple, range)

  Statement 1

  Statement 2

**Ex:**
  ```python
  for i in range (10):
	  print ('value',i)
  ```

**2)While Loop:**

  Repeats a block of code as long as the condition is true.

**Syntax:**

  while condition

  statements

  increment/decrement

**Ex:**
  ```python
  i=0
  while i<5
	  print('Value is:',i)
	  i=i+1
  print("Thank You")
  ```

### **Jump Statements:**

  Their are three types of statements:

  1. Pass
  2. Break
  3. Continue

**1)Pass:**

  If we don’t want to write any statement inside the loop then we can use pass.

**Ex:**
  ```python
  if 10>5:
	  pass
  else:
	  Pass
  if 10>5:
	  pass
  else:
	  print("Hello")
  ```

**2)Break:**

  Break is used to terminate a loop.

**Ex:**
  ```python
  for i in range(10):
	  if i==2:
	  break
	  print(i)
  print("Last Line")
  ```

**3)Continue:**

  It skip the current execution and jumps to the next sequence of elements/iteration.

**Ex:**
  ```python
  for i in range (10)
	  if i==2:
		  continue
	  print(i)
  print("Last Line")
  ```

**For else and While else:**

**for else:**
  ```python
  for i in range(10)
	  if i==2:
		  break
	  print(i)
  else:
	  print("I am form else block")
  print("Last Line")
  ```

**Ex:**

  In for loop if all the iteration successfully executes then only else block will execute.

**while else:** 
  ```python
  i=0
  while i<5:
	  if i==3:
		  break
	  print('Value:',i)
	  i=i+1
	  else:
		  print("I'm form else block")
  print("Last Line")
  ```

**enumerate()**

  It is used if we want to get the value with the index no. from the sequence of elements (list, set, range)

**Ex:**
  ```python
  for idx,value in enumerate([10,20,30]):
	  print(idx,"____", value)
  ```
