# Operators

**1.Arithmetic Operators:**

  Python [**Arithmetic operators**](https://www.geeksforgeeks.org/python-arithmetic-operators/) are used to perform basic mathematical operations like **addition, subtraction, multiplication** and **division**.

  | Operator | Operator Name |
  | --- | --- |
  |       **`+`** | Addition |
  |       **`-`** |  Subtraction |
  |       **`*`** | Multiplication |
  |       **`/`** | Division |
  |       **`%`** | Modulus  |
  |      **`//`** | Floor Division |
  |      **`**`** | Exponent |

**Syntax:**
  ```python
  # Variables
  a = 15
  b = 4

  # Addition
  print("Addition:", a + b)  

  # Subtraction
  print("Subtraction:", a - b) 

  # Multiplication
  print("Multiplication:", a * b)  

  # Division
  print("Division:", a / b) 

  # Floor Division
  print("Floor Division:", a // b)  

  # Modulus
  print("Modulus:", a % b) 

  # Exponentiation
  print("Exponentiation:", a ** b)
  ```

**2.Comparison Operator:**

  In Python [**Comparison**](https://www.geeksforgeeks.org/python-object-comparison-is-vs/) [](https://www.geeksforgeeks.org/relational-operators-in-python/) of [**Relational operators**](https://www.geeksforgeeks.org/relational-operators-in-python/) compares the values. It either returns **True** or **False** according to the condition(Boolean Type Result).

  | Operator | Operator Name |
  | --- | --- |
  |      **`<`** | Less then |
  |      ****`<=` | Less then equal to |
  |      **`>`** | Greater then |
  |     **`>=`** | Greater then equal to |
  |     **`==`** | Equal to |
  |     **`!=`** | Not equal to |

**Syntax:**
  ```python
  a = 13
  b = 33

  print(a > b)
  print(a < b)
  print(a == b)
  print(a != b)
  print(a >= b)
  print(a <= b)
  ```

**3.Logical Operators:**

  Python [**Logical operators**](https://www.geeksforgeeks.org/python-logical-operators-with-examples-improvement-needed/) perform **Logical AND**, **Logical OR** and **Logical NOT** operations. It is used to combine conditional statements.

  Combine the multiple conditions as a single expression. 

  | Operator and Name |
  | --- |
  |             **and** |
  |              **or** |
  |             **not** |

**Syntax:**
  ```python
  a = True
  b = False
  print(a and b)
  print(a or b)
  print(not a)
  ```

**4.Bitwise Operators:**

  Python [**Bitwise operators**](https://www.geeksforgeeks.org/python-bitwise-operators/) act on bits and perform bit-by-bit operations. These are used to operate on binary numbers.

**Syntax:**
  ```python
  a = 10
  b = 4

  print(a & b)
  print(a | b)
  print(~a)
  print(a ^ b)
  print(a >> 2)
  print(a << 2)
  ```

**5.Assignment Operators:**

  Python [**Assignment operators**](https://www.geeksforgeeks.org/assignment-operators-in-python/) / Short-hand assignment Operators are used to assign values to the variables. This operator is used to assign the value of the right side of the expression to the left side operand.

**Syntax:**
  ```python
  a = 10
  b = a
  print(b)
  b += a
  print(b)
  b -= a
  print(b)
  b *= a
  print(b)
  b <<= a
  print(b)
  ```

**Explanation:**

  a=10 and b=a. So, the b value is 10 than b=10.

  b +=a means b=b + a. So,10+10=20.

  b -=a means b=b - a. So, 20 - 10=10.

  b *=a means b =b * a. So, 10 * 10=100.

**6.Identity Operators:**

  In Python, **is** and **is not** are the [**identity operators**](https://www.geeksforgeeks.org/python-membership-identity-operators-not-not/) both are used to check if two values are located on the same part of the memory. Two variables that are equal do not imply that they are identical. 

  ***is***

  *True if the operands are identical*

  ***is not***

  *True if the operands are not identical*

**Syntax:**
  ```python
  a = 10
  b = 20
  c = a

  print(a is not b)
  print(a is c)
  ```

**7.Membership Operators:**

  In Python, **in** and **not in** are the [**membership operators**](https://www.geeksforgeeks.org/python-membership-identity-operators-not-not/) that are used to test whether a value or variable is in a sequence.

  ***in***

  *True if value is found in the sequence*

  ***not in***

  *True if value is not found in the sequence*

**Syntax:**
  ```python
  x = 24
  y = 20
  list = [10, 20, 30, 40, 50]

  if (x not in list):
      print("x is NOT present in given list")
  else:
      print("x is present in given list")

  if (y in list):
      print("y is present in given list")
  else:
     print("y is NOT present in given list"
  ```

**8.Ternary Operator:**

  In Python, [**Ternary operators**](https://www.geeksforgeeks.org/ternary-operator-in-python/) also known as conditional expressions are operators that evaluate something based on a condition being true or false. It was added to Python in version 2.5.

  It simply allows testing a condition in a **single line** replacing the multiline if-else making the code compact.

**Syntax :**  

[on_true] if [expression] else [on_false]* 

**Syntax:**
  ```python
  a, b = 10, 20
  min = a if a < b else b

  print(min)
  ```
