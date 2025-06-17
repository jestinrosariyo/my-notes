# **Types of Quotation Marks in Python for Strings**

**1) Single Quotes (' ')**

	Used for **single-line strings**.

	name = 'Any Name'

**2) Double Quotes (" ")**

	Also used for **single-line strings**, especially useful if the string contains an apostrophe.

	message = "You're amazing"

**3) Triple Quotes (''' ''' or """ """)**

	Used for **multi-line strings** or **docstrings**.

	poem = '''Roses are red,

	Violets are blue,
	
	Python is sweet,

	And so are you.'''

**Note:**

	By using single or double quotation we can create only single line String data.
	By using triple single or triple double quotations we can create multiline string data

**Python Commands:**

	1.Single line → Use #To command program with in One Line or Single Line.

	2.Multi line  → Use””” “”” or ‘’’ ‘’’ To command Program with multiline.

**Python Keywords:**

	- Python keywords are predefined reserved words.
	- Every keyword having its own behavior and we cannot change that keyword behavior.
	- We have 35 keyword in Python.
	- Python is providing one predefined module called as “Keyword”.
	- In this keyword module all 35 keywords available.
	- If we want to use that keyword than use `import keyword`.

**Syntax:**

```python
import keyword

print(keyword.kwlist)

#Fuctions
c=len('Jestin Rosariyo')
print('Print the Lenth of:',c)

f=len(keyword.kwlist)
print('Print the lenth of :',f)

g=len(['one','two','three'])
print('Print the lenth of:',g)

name="Naveen"
print(name)

print(type(name))

print(id(name))

print(len(name))

print('---------------------------')

#Examples
print(keyword.iskeyword("class"))

print('if' in keyword.kwlist)

print(50 in [10,20,30,40])

print('---------------------------')
print('The Condition:',10<5)

a=50
b=None
print(a)

x=20
print(x)

#Statements
if 50>30:
    print('Good')
else:
    print('Sad')
```

**Explanation:**

- import keyword
    
    Used to import get predefined reserved words.
    
- print(keyword.kwlist)
    
    Used to view the keywords.
    
    **['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']**
