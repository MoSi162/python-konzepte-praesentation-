



# Python Presentatiom


---

## 1. 📚 Intro to Python

Python is an easy-to-understand, powerful programming language.

Versatile: It is used in many fields such as web development, data analysis, artificial intelligence, scientific computing, automation, and more.



---

## 2. 📚 Variablen & 📚 Datatypes

# String     
name = “John”        
# Integer    
age = 30            
# Float      
pi = 3.14           
# Boolean    
is_happy = True      



# String (text)
name = "John"
print(name)                 # Output: John
print(name.upper())         # Output: JOHN

# Integer (whole number)
age = 30
print(age)                  # Output: 30
print(age + 5)              # Output: 35

# Float (decimal number)
pi = 3.14
print(pi)                   # Output: 3.14
print(pi * 2)               # Output: 6.28

# Boolean (True/False)
is_happy = True
print(is_happy)             # Output: True
print(not is_happy)         # Output: False

# You can also combine them in a message using f-strings
print(f"My name is {name}, I am {age} years old. Pi is about {pi}. Am I happy? {is_happy}")



---

## 3. 🧩 Strings

text = “Hello” 
print(text.upper())     
# “HELLO” 
print(f”Hi {name}!”)    
# f-String


# Store a string in a variable
name = "Max"

# Make all letters uppercase
text = "Hello"
print(text.upper())   # Output: HELLO

# Make all letters lowercase
print(text.lower())   # Output: hello

# f-String: insert variables into a string
print(f"Hi {name}!")  # Output: Hi Max!

# Concatenate strings (join together)
greeting = "Hello " + name
print(greeting)       # Output: Hello Max

# Length of a string
print(len(name))      # Output: 3



---

## 4. 📚 For-Loops
1#
 for i in range(3): print(f”Durchlauf(forloop) {i}”)


# Loop 3 times (i will be 0, 1, 2)
for i in range(3):
    print(f"Durchlauf (for loop) {i}")

# Output:
# Durchlauf (for loop) 0
# Durchlauf (for loop) 1
# Durchlauf (for loop) 2

2️# 
Loop over a list

names = ["Anna", "Max", "John"]

for name in names:
    print(f"Hello {name}!")


3#  
 Nested loops (loop inside a loop)

for x in range(2):
    for y in range(3):
        print(f"x={x}, y={y}")



---

## 5. 📚 Funktionen

def greet(person): 
return f”Hallo, {person}!”
print(greet(“Malika”))



you can also greet multiple people....

def greet(person):
    return f"Hallo, {person}!"

names = ["Tim", "oualid", "oksana"]
for name in names:
    print(greet(name))

# Output:
# Hallo, Anna!
# Hallo, Max!
# Hallo, John!




---

## 6. 📚 Collections of Data




#Liste (List)
zahlen = print(zahlen) 

#Dictionary
grades = {“malika”: 1, “Mo”: 2} print(grades“Malika”)  

#Set
fruechte = {“Apfel”, “Banane”, “Apfel”} print(fruechte)  







---

## 7. 📚 Klassen – Einführung in OOP

class Person: def init(self, name): self.name = name



def greet(self):
    return f"Hi, ich bin {self.name}"





p = Person(“malika”) print(p.greet())




---



Fragen? 🚀







