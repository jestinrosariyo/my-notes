# Type Casting
  The process of Converting a value of  one Datatype into another Datatype.

**Example:**

(String ,Integer, Float, Boolean)

**Syntax:**
  ```python
  a=int("10")
  b=int("20")
  c=(a+b)
  print(c)
  ```
**o\p:**
  30

**Explanation:**
  - A value in the Quotes without mention datatype is always consider as an string.
  - So, need to mention the datatype of the value or input.

### Two Types of Type Casting:
  1. Explicit type casting.
  2. Implicit type casting.

**1.Explicit type casting:**

  For every data type one type casting function will be there.

**Ex:**
int → int()

float → float()

string →str

boolean →bool

**2.Implicit type casting:**

  It covert value or variable into a different data type automatically is called implicit type casting.

### **What is input()?**
  - The input()function is used to **take user input** in Python.
  - It always returns the input as a **string**(even if the user enters a number).

**Syntax:**
  variable = input("Prompt any message")

**Example:**
  ```python
  name=input("Enter the Name:")
  print('Welcome'+ name + '!')
  ```

**o/p:**
  Enter the Name: Naveen

  Welcome Naveen !

### How to get input form User?

**Syntax:**
  ```python
  a=int(input())
  b=int(input())
  c=(a+b)
  print(c)
  ```

    a=10
    
    b=20

    (a + b)10+20=30(c)

**o\p:**
  30

**Converting Input:**
  Since the input() return the string, you often need to convert.

**Ex:**
  ```python
  age=input()  #age is String
  age=int(age) #converting to Integer
  print("Next year you will be",age+1)

# Shortcut
  age=int(input("Enter your age:"))  #directly convert's to Interger
  ```

**Program for Arithmetic Operator:**
  ```python
  # Python program to demonstrate arithmetic operators

  # Input two numbers from the user
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))

  # Perform arithmetic operations
  print("\n--- Arithmetic Operations ---")
  print("Addition:        ", num1 + num2)       # +
  print("Subtraction:     ", num1 - num2)       # -
  print("Multiplication:  ", num1 * num2)       # *
  print("Division:        ", num1 / num2)       # /
  print("Modulus:         ", num1 % num2)       # %
  print("Exponentiation:  ", num1 ** num2)      # **
  print("Floor Division:  ", num1 // num2)      # //
  ```

**Program for Type Casting:**
  ```python
  # Typecasting in Python

  # Taking input as a string
  num_str = input("Enter a number (string): ")
  print("Data type before typecasting:", type(num_str))

  # Converting string to integer
  num_int = int(num_str)
  print("After typecasting to int:", num_int)
  print("Data type after typecasting:", type(num_int))

  # Converting integer to float
  num_float = float(num_int)
  print("After typecasting to float:", num_float)
  print("Data type after typecasting:", type(num_float))

  # Converting float to string
  num_str_again = str(num_float)
  print("After typecasting to string again:", num_str_again)
  print("Data type after typecasting:", type(num_str_again))
  ```
