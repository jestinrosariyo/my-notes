# Datatypes

  Variables can store data of different types, and different types can do different things.

  1. Datatypes are some of the keywords of the programming language, which are used to specify what type of data has to be store into the variables.
  2. With out datatypes we can not store the data into the variable. 
  3. Python supports the dynamic datatypes. (i.e) at the time of execution of program datatype of the variable will be decided based on the data which is assigned to that variable.

**Ex:**

  a=10

  int, long, float (these keywords are acting as datatype in the Python ).

**Types:**

***1.Numeric Type***

  - Integer.
  - Float.
  - Complex Number.

***2.Sequence Types***

  - String.
  - Tuple.
  - List.
  - Range.

***3.Mapping Type***

  - Dictionary.

***4.Boolean Type***

  - Bool.

***5.Set Type***

  - Set.
  - Frozeset.

***6.Binary Type***

  - Bytes.
  - Bytearray.
  - Memoeyview.

***7.None Type***

  - NoneType.

**Syntax:**

  a=10

  print(type(a))

**o\p:**

  <class ‘int’>

**Syntax:**

  a=Example

  print(type(a))

**o\p:**

  <class ‘str’>

  Python data types are categorized into two types.

  1.Fundamental or Primitive data type.
  2.Collections or Non-Primitive data type.

**1.Fundamental or Primitive data type:**

  The variables which are represented with functional data types are stores the address of the object in which we can represent only one element.

***1. Numbers***
    - int
    - float
    - complex
    
    **Ex:**
    
    num= 2+3j
    
    j → represents the imaginary unit 
    
    j=2
    
    2+3*2
    
    num=8
    
***2. Boolean types***

***3. String types***

**2.Collections or Non-Primitive data type:**

  The objects which are maintaining the group of elements at a time are called collection of data type.

**Ex:**

  ```python
  my_list=[1,2,'apple' , 'banana']
  ```

  1. Using one variable reference, if you are able to store multiple values in the memory and these data types comes under with collection data types.
  2. Collection datatypes contains the different data types of values in a memory at a time.
  3. Python is providing so many collection data types.

**Example:**

**1.List type:**

  List are ordered collections of items, mutable and can contain elements of different data types. List are represented by the list type.

**Ex:**
  ```python
  my_list=[1,2, 'apple' , 'banana']
  ```

**2.Tuple type:**

  Tuples are ordered collections of items, immutable , and typically used to store heterogeneous

  data. Tuples are represented by tuple type.

**Ex:**
  ```python
  my_tuple=(1,2, 'apple' , 'banana')
  ```

  **3.Set type:**

  Python provides two set data type

  1. set: Represents an unordered collection of unique elements. Ex: my_set ={1, 2, 3, 4}
  2. frozen set: Similar to sets but immutable. Ex: my_frozen_set = ({1, 2, 3, 4,})

**4.Dictionary type:**

  dict: Represents a collection of key-_value pairs, where each key is unique.

**Ex:** 
  ```python
  my_dict = {'name': 'Pavan' 'age' : 23}
  ```

### Immutable and Mutable object

  - Everything in python is an object.
  - All the data types are nothing but object in python, All objects are having their own behaviors.
  - Based on behavior all the objects are classified into two different types, they are mutable and immutable types.

**All python major data types are again divided into 2 types:**

***1.Immutable types***

  The value can’t be changed or removed.(object are fixed)

  - Number (int, float, complex)
  - Boolean (bool)
  - String (str)
  - Tuple (tuple)
  - Frozen set (Frozenset)

**Syntax:**
  ```python
  a=(10,20,30,40)  # Tuple List
  print(len(a))    # Length of the Tuple List
  print(a[2])      # Position of the value in Tuple
  a[1]=50          # Try to add value in List but can't add and throw's TypeError: 'tuple' object does not support item assignment
  ```

***2.Mutable types***

  The value can be changed and stored at the same memory address or location.

  - Lists (list)
  - Sets (set)
  - Dictionaries (dict)

**Syntax:**
  ```python
  a=[10,30,40]     # List
  print(len(a))    # Length of the List
  print(a[2])      # Position value of 2 in List
  a.append(20)     # Add value 20 in List
  print(a)         # Print the List
  del a[2]         # Delete the postion value 2 in List
  print(len(a))    # length of the List
  print(a)         # print the List
  ```

### Difference between mutable and immutable objects?

      A mutable object can be changed after it is created, and an immutable object cannot be changed after created.

### **String Data type:**

     Any character which is available in the single or double quotation is called string.

**Ex:**
  ```python
  s='Hello'
  s1="Hello"
  s2='''Hello'''
    s3="""Hello"""
```

  - String allows duplicate values.
  - String follows inserting order.
  - String is immutable object not an editable object.
  - String supporting concatenation behavior.
  - String supports repetition behavior.
  - Every element in string contains unique index value.
  - String contains both forward and backward indexing.
  - Forward indexing starts from 0 represents the first element in the given object and backward starts form -1  last element in the give object.

**Ex:**

       0    1  2   3  4  5  6  7 

s=   S    r   i   n   i   v  a   s

      -8 -7 -6 -5 -4 -3 -2 -1

**Example:**
  ```python
  s=srinivas
  s[-1]
  s[-2]
  s[1]

  # String support sliving concept
  s[0:3]    #sri o/p
  s[0:3:1]  #sri o/p
  s[1:-1:1] #riniva o/p
  ```
# Python Tuple Data Type:

      The sequence of ordered elements which are separated by comma and enclosed in between parenthesis or without  parenthesis is called as tuple object.

**Ex:** 
  ```python
  t=(1,2,3,4) or 
  t1=1,2,3,4,5
  # Creating single element tuple
  t=10
  type(t)
  # <class 'int'>

  t=10,
  type(t)
  # <class 'tuple'>

  t0=("Hi")
  type(t0)
  # <class 'str'> 

  t0=("Hi,")
  type(t0)
  # <class 'tuple'>
  ```

  → Tuple allows duplicate values.

  → Tuple follows inserting order.

  → Tuple is a immutable object not editable object.

  → Tuple supporting concatenation behavior.

  ```python
  (1,2)+(3,4)
  # o/p:
  (1,2,3,4)
  ```

  → Tuple also supports repetition.

  ```python
  (1,2,3)*3
  # o/p:
  (1,2,3,1,2,3,1,2,3)
  ```

  → Every element in tuple object contains unique index value.

  → Tuple object contain both forward indexing and backward indexing.

  →Tuple supporting slicing.

  s[0:3:1]

  → Tuple object allows both immutable and mutable  based on types of data inside it.

  ```python
  (10,20.40,"Hai",(1,2,3),[1,2],{1,2},{1:10})
  ```

## Two Type of methods in tuple:

**1.count()**
  ```python
  t=(10,20,30,40,10,20)
  t.count(20)
  ```

**2.index()**
  '''python
  t=(10,20,30,40,10,20)
  t.index(2)
  '''
