# Python cheatsheet

## Data types
x = 42          # int
y = 3.14        # float
s = "hello"     # string
l = [1, 2, 3]   # list
d = {"a": 1}    # dict

## Control flow
if x > 0:
    print("positive")

for i in range(10):
    print(i)

## Functions
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"

## List comprehensions
squares = [x**2 for x in range(10)]
evens = [x for x in range(20) if x % 2 == 0]
