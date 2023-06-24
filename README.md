
## $ whoami

- Beven Nyamande *(Bcom Finance)* aka 0xbeven and a bug hunter
- First Alumni Muzinda Hub an Econet Incubation and www.treehouse.com
- Founder of Crontab www.crontab.co.zw
- Python backend developer
- Flask and Django enthusiast, data science @ kaggle etc 
- Cyber Security Researcher, bug bounty @0xbeven hackerone etc
- Plays more CTFs @ Tryhackme.com, **former #1 in Zimbabwe** now #3 :(


- **The Zen of Python, by Tim Peters :)** 

```python
import this
```


- The above is the basis and blocks of the python programming language

**Slide 1: Introduction to Python programming and its uses**

-   Introduce Python and its popularity as a programming language
-   Explain the various uses of Python in different fields such as **web development, data analysis, machine learning**, etc.

**Slide 2: Installing Python on your computer**

-   Discuss the different ways of installing Python on your computer such as downloading from the official website or using package managers like Anaconda
-   Provide step-by-step instructions for installation

**Slide 3: Setting up virtual environment for your Python projects**

-   Explain what virtual environments are and why they are useful
-   Provide instructions for creating and activating a virtual environment in Python using `venv` or `virtualenv`

```bash
python -m venv venv
source venv/bin/activate

# installing modules and libraries in python
# introduction to pip install flask
# simple web application

pip install flask
```

**Slide 4: Understanding Python syntax and variables**

-   Discuss the basic syntax of Python and how it differs from other programming languages
- Dynamically typed 
-   Explain variables and their types in Python

```python
print("Hello, world!")

```

Here are the websites for  online coding games:

1.  CodeCombat: [https://codecombat.com/](https://codecombat.com/)
2.  CheckiO: [https://checkio.org/](https://checkio.org/)
3.  HackerRank: [https://www.hackerrank.com/domains/python](https://www.hackerrank.com/domains/python)
4.  PyCharm Edu: [https://www.jetbrains.com/pycharm-edu/](https://www.jetbrains.com/pycharm-edu/)
5.  Codingame: [https://www.codingame.com/start](https://www.codingame.com/start)
6.  Codewars: [https://www.codewars.com/](https://www.codewars.com/)


**Slide 5: Data types in Python: strings, integers, floats, Boolean, etc.**

-   Introduce the different data types in Python and their uses
```python

name = "Beven" # string variable
decimal = 1.02 # float variable
number = 1 # number definition
is_bool = True # boolean can either be true or false


# Other examples

string_example = "This is a string."
integer_example = 5
float_example = 3.14
boolean_example = True
```

**Slide 6: Basic arithmetic operations in Python**

-   Discuss the basic arithmetic operations such as addition, subtraction, multiplication, and division
-   Provide examples of how to perform these operations in Python

```python

addition_result = 2 + 3
subtraction_result = 7 - 4
multiplication_result = 5 * 6
division_result = 10 / 2
```

**Slide 7: Conditional statements in Python: if, elif, and else statements**

-   Explain conditional statements and their importance in programming
-   Provide examples of how to use if, elif, and else statements in Python

```python
age = 18

if age < 18:
    print("You are not old enough to vote.")
elif age == 18:
    print("Congratulations, you can now vote!")
else:
    print("You are old enough to vote.")```


**Slide 8: Loops in Python: for and while loops**

-   Introduce the concept of loops and their uses in programming
-   Provide examples of how to use for and while loops in Python

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)

# While loops

i = 0
while i < 5:
    print(i)
    i += 1
```

**Slide 9: Functions in Python: defining and calling functions**

-   Explain what functions are and why they are useful
-   Provide examples of how to define and call functions in Python

```python
def greet(name):
    print("Hello, " + name + "!")

greet("John")
greet("Jane")
```

**Slide 10: Lists in Python: creating, accessing, and modifying lists**

-   Introduce the concept of lists and their uses in programming
  
```python
fruits = ["apple", "banana", "cherry"]
```
-   Provide examples of how to create, access, and modify lists in Python

```python

# Access lists
print(fruits[1])

# List modification

fruits.append("orange")
```


**Slide 11: Tuples in Python: creating and accessing tuples**

-   Introduce the concept of tuples and how they differ from lists

```python
fruits = ("apple", "banana", "cherry")
```
-   Provide examples of how to create and access tuples in Python
```python
print(fruits[1])
```
**Slide 12: Dictionaries in Python: creating and accessing dictionaries**

-   Explain dictionaries and their importance in Python

```python
person = {"name": "John", "age": 25, "occupation": "Engineer"}
```


-   Provide examples of how to create and access dictionaries in Python
```python
print(person["name"])
```

**Slide 13: Sets in Python: creating and accessing sets**

-   Introduce sets and their uses in Python

```python
fruits = {"apple", "banana", "cherry"}

```
-   Provide examples of how to create and access sets in Python

**Slide 14: File handling in Python: reading and writing files**

-   Explain file handling in Python and its importance

```python
file = open("example.txt", "r")
content = file.read()
print(content)
file.close()
```
-   Provide examples of how to read and write files in Python

```python
file = open("example.txt", "w")
file.write("Hello, world!")
file.close()
```



**Slide 15: Exception handling in Python: try, except, and finally statements**

-   Discuss exception handling and its importance in programming


```python
try:
    age = int(input("Enter your age: "))
except ValueError:
    print("Invalid input. Please enter a number.")
else:
    print("Your age is", age)
finally:
    print("Program ended.")
```
-   Provide examples of how to use try, except, and finally statements in Python


**Slide 16: Object-oriented programming in Python: classes and objects**

-   Introduce object-oriented programming and its advantages
-   Provide examples of how to create classes and objects in Python

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        print("Hello, my name is", self.name, "and I am", self.age, "years old.")

person1 = Person("John", 25)
person2 = Person("Jane", 30)

person1.greet()
person2.greet()
```

**Slide 17: Inheritance in Python: creating a subclass**

-   Discuss inheritance and its importance in object-oriented programming
-   Provide an example of how to create a subclass in Python


```python
class Animal:
    def __init__(self, name):
        self.name = name

    def make_sound(self):
        pass

class Dog(Animal):
    def make_sound(self):
        print("Woof!")

dog = Dog("Rover")
dog.make_sound()
```

**Slide 18: Modules in Python: importing modules**

-   Explain modules and their uses in Python
-   Provide examples of how to import modules in Python

```python
import math

result = math.sqrt(25)
print(result)
```

**Slide 19: Standard libraries in Python: math, datetime, random, etc.**

-   Discuss the various standard libraries available in Python and their uses
-   Provide examples of how to use some of the commonly used standard libraries in Python

```python
from datetime import datetime

current_time = datetime.now()
print(current_time)
```

**Slide 20: Working with APIs in Python: using requests module**

-   Explain what APIs are and their importance in programming
-   Provide examples of how to work with APIs in Python using the requests module

```python
import requests

response = requests.get("https://api.example.com/data")
data = response.json()

print(data)
```

**Slide 21: Debugging in Python: using pdb module**

-   Discuss debugging and its importance in programming
-   Provide an example of how to use the pdb module for debugging in Python

```python
import pdb

def divide(a, b):
    result = a / b
    return result

pdb.set_trace()
result = divide(10, 2)
print(result)
```

**Slide 22: Using external libraries in Python: installing and using external packages**

-   Explain how to install and use external libraries in Python
-   Provide examples of some popular external libraries in Python and their uses

```python
!pip install pandas

import pandas as pd

data = pd.read_csv("example.csv")
print(data.head())
```

**Slide 23: Web development with Python: using Django framework**

-   Introduce the Django framework and its uses in web development
-   Provide examples of how to create a basic web application using Django

```python
pip install django

django-admin startproject projectname

python manage.py runserver
```
