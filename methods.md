# Python String Methods

1.`capitalize()` → Change the first letter of a string to uppercase.
  ```python
  a="english language"
  a1=a.capitalize()
  print(a1)
  ```

2.`title()` → Change the first letter of each word to uppercase.
  ```python
  b="english is an easy language"
  print(b.title())

  print("I can do it".title())
  ```

3.`swapcase()` →Swap the case of each letter in a string.
  ```python
  c="ENGLISH LANGUAGE"
  print(c.swapcase())

  c1="ENGLISH language"
  print(c1.swapcase())
  ```

4.`lower()` → Convert all letters in a string to lowercase.
  ```python
  d="I AM LEARNING PYTHON"
  print(d.lower())
  ```

5.`upper()`  → Convert all letters in a string to uppercase.
  ```python
  d="I AM LEARNING PYTHON"
  print(d.upper())
  ```

6.`isupper()`/`islower()` → Is to check whether the letters are in upper case or lower case.
  ```python
  d="I AM LEARNING PYTHON"
  print(d.islower())
  print(d.isupper())
  ```

7.`isnumeric()` / `isdigit()`→ Check if a string contains only numeric characters.
  ```python
  print("12345".isnumeric())
  print("12345".isdigit())
  ```

8.`isalpha()` → Check if a string contains only alphabetic characters.
  ```python
  print("abcde".isalpha())
  ```

9.`isalnum()` → Check if a string contains alphanumeric characters.
  ```python
  print("abcd1234".isalnum())
  ```

10.`isspace()` → Check if a string contains only whitespace characters.
```python
  print(" ".isspace())
  ```

11.`len()` → Get the length of a string.
  ```python
  e="I will make it happen one day"
  print(len(e))
  ```

12.`split()` → Split a string into a list of words. Identify through default delimited space.
  ```python
  e="I will make it happen one day"

  print(len(e.split()))

  print(e.split("make"))

  print(e.split(" ",3))
  ```

13.`splitlines()` → Split a multiline string into lines.
  ```python
  f='''I like to travel
  I like to read books
  I like to learn new things
  i like to cook'''
  print(f)
  print(f.splitlines())
  print(len(f.splitlines()), "lines available") 
  ```

14.`count()` → It check how many times the given string is repeated.
  ```python
  # Count occurrences of a character in a string
  print("never ever hever".count("e"))
  print("never ever hever".count("e",0,10)) # count in a specific range
  print("never ever hever".count("e",1,8))
  ```

15.`index()`→ It return the first occurrence index position. Left to right. Throw’s error.
  ```python
  # Index of a character in a string
  print("the world is full of surprises".index("f"))
  print("the world is full of surprises".index("s",0,20))
  ```

16.`rindex()`→  It return the first occurrence index position. right to left.
  ```python
  # Rindex of a character in a string
  print("the world is beautiful".rindex("l"))
  print("the world is beautiful".rindex("l",0,20))
  ```

17.`find()` → Finds whether the object inside the string. Right to left. Throw’s no error.
  ```python
  # Find a character in a string
  print("Developing is fun".find("p"))
  print("Developing is fun".find("p",7,12))
  ```

18.`rfind()` → Finds whether the object inside the string. Left to right.
  ```python
  # Rfind a character in a string
  print("Developing is fun".rfind("f"))
  print("Developing is fun".rfind("f",0,12))
  ```

19.`strip()` → Remove leading and trailing spaces.
20.`lstrip()` → Remove leading spaces. Left side.
21.`rstrip()` → Remove trailing spaces. Right side.
  ```python
  # Remove leading whitespace from a string
  print("   Jackson William    ".lstrip()) # Remove leading spaces
  print("   Jackson William    ".rstrip()) # Remove trailing spaces
  print("   Jackson William    ".strip())  # Remove leading and trailing spaces
  ```

21.`startswith()` → Check if a string starts with a specific substring.
22.`endswith()` → Check if a string ends with a specific substring.
  ```python
  # Check if a string starts with a specific substring
  Character="I am not that good at coding"
  print(Character.startswith("I am")) # Check if it starts with "I am"

  # Check if a string ends with a specific substring
  print(Character.endswith("coding")) # Check if it ends with "coding"
  ```

23.`replace()` → Replace a old substring in a  new string.
  ```python
  # Replace a substring in a string
  text="Chennai is a traffic city"
  print(text.replace("Chennai","Bangalore")) # Replace "Chennai" with "Bangalore"

  city="Chennai is beautiful city Chennai is a traffic city Chennai is a good city"
  print(text.replace("Chennai","Bangalore",2)) # Replace first two occurrences of "Chennai" with "Bangalore"
  ```

24. `join()` → Join a list of strings into a single string
  ```python
  # Join a list of strings into a single string
  na="Naveen"
  ba=" is"
  ca=" good boy"
  da="".join([na, ba, ca]) # Join the strings with no separator
  print(da)
  ```
