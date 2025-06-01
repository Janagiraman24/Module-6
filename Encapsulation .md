# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length  # private variable
        self.__breadth = breadth    # private variable

    def print_dimensions(self):
        # Accessing and printing private members within the class
        print(self.__length)
        print(self.__breadth)

# Creating an object
r = Rectangle(5, 3)

# Accessing private variables using class method
r.print_dimensions()

```
## Output
![image](https://github.com/user-attachments/assets/9a66c95b-659f-4d45-8e40-e1bc4474a851)

## Result
Thus the program has been successfully executed.
