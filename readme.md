## Class (Blueprint for creating Objects)
- Self Keyword - “self” refers to the instance of the class that is currently being used

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

## Abstraction (Hiding details from users)
## Encapsulation
## Inheritance
## Polymorphism
