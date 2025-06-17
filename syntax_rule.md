# Syntax Rules
**1.What is syntax rule?**
  Syntax is the set of rules that define how a python program is written and interpreted.
  
**2.Why is python syntax important?**
  If you break the syntax rule, you will get error and your program won’t run.
  
**3.What is python syntax rules?**

  |             **Rule** |                           **Description** |                  **Example** |
  | --- | --- | --- |
  | Indentation | Use space(Usual space) to define code block | if Ture print(”YES”) |
  | Case Sensitive | Name and name are different | Name=”John”   name=”Naveen” |
  | No Declaration | No need to declare variable type | x=10 |
  | Colon | Used to start blocks | def color(): |
  | Commands | For single line commands | #This is a command |
  | Line Continuation | Use \ for long line | total=1+2+                               \3+4   |
  | Importing | Use import to bring in modules | import keyword |
  | String in quotes | String must be inside ‘ ‘ or “ “ quotes | msg=”Hello” |

**Literals**
  - Literals are nothing but data part.
  - In python data is technically called as literals.
  - Literals are classified into different types they are like…
![Python-Data-Types.webp](attachment:a6defacb-59f1-47ad-ad56-a20308b3af75:Python-Data-Types.webp)

**Python Constants**
  - The value which are fixed are called as constants.
  - In the python programming language constants are types of variables whose value cannot be allowed or changed after initialization.
  - Constants variable should be in uppercase, it is meaning that the value should not change.
  - 
**Ex:** 
    MAX_AGE =25
    is a constant variable, which mean no other developer should change this variable.
    
**Syntax:**
  ```python
  total=1+2+\
         3+4
  print("The total values:",total)

  # ComplexType
  a=3+2j
  print("The complex number is:",a)

  # Contant Variable
  MAX_AGE=22
  print("The max age is:",MAX_AGE)

  # Aruthmatic Operator
  # Addition
  print(10+40)
  print(10+30.50)
  print(10.50+30)

  # Concatenation Operator
  print("Hello"+"World")

  print('10'+'20')

  print(10+'20') #TypeError: can only concatenate str (not "int") to str

  print("The sum is:",+10) #TypeError: unsupported operand type(s) for +: 'str' and 'int'

  print("The sum of:",10)

  print("The sum of:"+str(10))
  ```
