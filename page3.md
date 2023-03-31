# OBJECT ORIENTED PROGRAMMING: OVERRIDE & POLYMORPHISM

Within Object Oriented Programming there are many fundamental conepts that should be known by us programmers.

The two being focused on this page will be:
- Override
- Polymorphism

## Override
- When two methods have the same method name and parameters

Here's an example:

```python
# Example of Override

class Human
    def study(self):
        print('Human is studying.')

class Student(Human):
    def study(self):
        print('Student is studying')

human = Human()
student = Student()

human.study()   # prints 'Human is studying'
student.study() # prints 'Student is studying'

```

In this example, the `Student` class overrides the `study()` method that is defined in the `Human` class. When the `study()` method is called on a `Student` object, it uses the `study()` methiod defined in the `Student` class. 

However, when the `study()` method is called on a `Human` object, it uses the `study()` method defined in the `Human` class, because the `Human` object is not and instance of the `Student` class and does not have access to the `study()` method defined in the `Student` class. This is how method overriding works in Python.



