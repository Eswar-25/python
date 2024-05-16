**Variables**

# Naming a variable
name = "Bard"
# Using a variable
print("Hello, my name is", name)


**Data Type**

# Integers
age = 25

# Float
pi = 3.14

# String
greeting = 'How are you?'

# Boolean
is_sunny = True


**Operators**

# Arithmetic operators
result = 10 + 5
difference = 14 - 7

# Comparison operators
is_equal = 10 == 10  # True
is_greater = 5 > 10  # False


**Indentation**

# Notice how the print statement is indented
if age > 18:
    print("You are an adult")


**Control Flow (if statement)**

age = 15

if age >= 18:
    print("You can vote")
else:
    print("You cannot vote yet")


**Loop (for loop & While loop)**

# Looping through a list of numbers
numbers = [1, 2, 3, 4, 5]

for number in numbers:
    print(number)

# while loop

count = 0
while count < 5:
  print("Count:", count)
  count += 1  # Incrementing the counter


**Function**

def greet(name):
  """This function greets a person by name."""
  print(f"Hello, {name}!")

greet("Alice")  # Calling the function


**Modules**

# Importing a module (math)
import math

# Using a function from the module
area_of_circle = math.pi * (radius**2)


**Classes and Objects**

class Car:
  """This class represents a car."""
  def __init__(self, make, model, year):
    self.make = make
    self.model = model
    self.year = year

  def accelerate(self):
    print(f"The {self.make} {self.model} is accelerating!")

my_car = Car("Tesla", "Model S", 2024)
my_car.accelerate()







