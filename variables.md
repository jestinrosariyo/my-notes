# Variables
  - Variable is used to accessing the value from the memories.
  - It is a storage container that add data and values.
  - String variables can be declared either using Single or Double quotes.

**Variables and its dimensions:**
  - 1.Name → Identify the Variable.
  - 2.Datatype → Determine the type, memory required and operations that can be performed on it.
  - 3.Address → Specify where it is stored.
  - 4.Value → Data held by the Variable.
  - 5.Lifetime → Specify how long it will be stored in memory.
  - 6.Scope → Specify where it can be accessed.

- **Syntax:**
  ```python
  a=10
  b=20
  print(a+b)
  ```
- **o/p:**
  30
- **Explanation:**
  →a and b are variables.
  →10 and 20 are the Values.
- **Notes:**
  Python is a Dynamic typed Programming Language.

**How many ways to assign the values to variable?**
  **1)a=10**
    b=a
  a assigned value 10 and b assigned to a. So, a=10 and b=a(10) then b=10.
  By Using Unpacking also, a variable can get the value.

  **2)Unpacking:**
  - **Syntax:**
  ```python
  a,b,c='Hai'
  print(a)
  ```
**Explanation:**
  a→ H , b→ a ,c→ i
  Each variables are pointing towards their values.

  **3)Packing:**
  ```python
  a,b,c='Hai'
  d=a+b+c
  print(d)
  ```
  If, Both Variable and value must be Equal. Than only Program run’s other wise shows Insufficient
  variable equal to values or Insufficient values equal to variables.

**Syntax:**
  ```python
  #Variables
  a=10
  b=20
  c=30
  print(a)
  print(b)
  print(c)
  print("********************")

  a=10
  b=20
  c=(a+b*5)
  print(c)
  print("********************")

  #Various types of variables
  def add(a,b):
      return a+b

  a=10
  b=20
  c=(a+b)
  print(c)
  print("********************")

  #Unpaking
  a,b=("hi")
  print(a)
  print(b)
  print("********************")

  #Packing
  a,b=("hi")
  c=(a+b)
  print(c)
  print("********************")

  #Variable lenth Arguments
  a,*b=(10,20,30,40,50)
  print(a)
  print(b)
  print("********************")

  a,*b,c=(10,20,30,40,50)
  print(a)
  print(b)
  print(c)
  print("********************")

  #Assgin value in Single Line
  a,b,c=10,20,30
  print(a)
  print(b)
  print(c)
  print("********************")

  #Assgin value if Same
  a=b=c=20
  print(a)
  print(b)
  print(c)
  print("********************")
  ```
