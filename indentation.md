# Function and Indentation

**Def Keyword:**

  In Python, def is a **keyword** used to **define a function**. It tells Python you're about to create a function block.

- **Ex:**
    **def function_name(parameters):**
    
      **# function body**
    
    **statements**
    
       **return something**

**Syntax:**
  ```python
  #Function without retrun statement
  def display():
      print("Welcome to the game!")

  #Function with retrun statement
  def display1():
      return "Welcome to the game!"

  #Function with parameter and retrun statement
  def display2(name):
      return f"Welcome {name} to the game!"

  display()
  print(display1())
  print(display2("John"))
  ```

**What is Indentation?**
  - **Indentation** means **adding spaces or tabs** at the beginning of a line of code.
  - In Python, indentation is **very important**. It tells Python **which lines of code belong together**.
  - Unlike other languages (like C, Java, etc.) that use { } for blocks, **Python uses indentation to define blocks** (like inside loops, functions, conditionals, etc.).
  - For Better code readability purpose, indentation is required.

  ****If you don’t indent properly, Python will give you an IndentationError.

**Where Indentation is used?**

  - Inside a Function.
  - Inside a Loops.(for, while)
  - Inside a Conditional Statements.(if, else, elif)
  - Inside a Classes.

**Syntax:**
  ```python
  #Proper Way
  def display():
      print("Welcome to the game!")
  display()

  #Improper Way
  def display():
  print("Welcome to the game!")
  display()
  ```
