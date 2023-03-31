# OBJECT ORIENTED PROGRAMMING: ENCAPSULATION & INHERITANCE

Within Object Oriented Programming there are many fundamental concepts that should be known by us programmers.

The two being focused on this page will be:
- Encapsulation
- Inheritance


# Encapsulation
- The process of restricing the access to certain attributes and methods within a class/object
- Hiding information (very useful in terms of privacy & security; data protection)

Heres an Example:

```python
# Example of Encapsulation

class Human:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age # encapsulated age variable]
        self.gender = gender
    
    def get_age(self):
        return self._age

    def set_age(self, new age):
        self.age = new_age

```

In this example, the `Human` class has three instance variables: `name`, `age`, and `gender`. However, the `age` variable is encapsulated by adding an underscore before its name. This conventiion indicates that the variable should not be accessed directly from outside the class, but through a getter and setter method. 

And to touch on that, the `get_age()` method allows you to retrieve the value of age from outside the class, while the `set_age()` method allows you to update its value. This encapsulation helps to protect the data within the object from being accessed or modified inappropriately from outside the class. 

## Inheritance
-
- 

Here's an example:
```python
# Example of Inheritance


```

Description


Closing
