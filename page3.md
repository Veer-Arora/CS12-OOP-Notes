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

