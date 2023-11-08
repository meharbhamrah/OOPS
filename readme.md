## Class (Blueprint for creating Objects)
- Self Keyword - “self” refers to the instance of the class that is currently being used
- - Init Method (by default method in python)

        class Dog:
          def __init__(self, name, age):
              self.name = name
              self.age = age
- Attributes are always public and can be accessed using the dot (.) operator. Eg.: Myclass.Myattribute

## Object (Object built from class)
- **Reference = dynamics_memorykeyword constructor()**
- **Types of binding**
  - Static Binding
  
        class Shape:
           def draw(self):
             pass
    
        class Circle(Shape):
           def draw(self):
             print("Drawing a circle")
    
        class Square(Shape):
           def Square(Shape):
             print("Drawing a square")
    
        - Static binding based on variable type
           shape = Shape()
           circle = Circle()
           square = Square()

        shapes = [shape, circle, square]
    
  - Dynamic Binding

        - Dynamic Binding
        shapes = [Shape(), Circle(), Square()]

## Abstraction (Hiding details from users)

## Encapsulation
## Inheritance (Parent class functions can be used in child class)
- Method Overloading (Same Class, Same Name but Different Parameters)

      class Calculator:
        def add(self, a , b):
           return a+b

        def add(self, a, b, c):
           return a+b+c
  
      calc = Calculator()
      result = cal.add(5, 6)
      print(result)
      - will raise error because only latest defined method will be used
## Polymorphism
