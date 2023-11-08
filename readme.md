## Class (Blueprint for creating Objects)
- Self Keyword - “self” refers to the instance of the class that is currently being used

      class Dog:
        def __init__(self, name, age):
            self.name = name
            self.age = age
- Attributes are always public and can be accessed using the dot (.) operator. Eg.: Myclass.Myattribute

## Instance (Object built from class)
- Static Instance

      Dog()
- Dynamic Instanace

      pet = Dog()
