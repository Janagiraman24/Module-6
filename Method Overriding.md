# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
class Fish:
    def info(self):
        print('fish')

class Shark(Fish):
	def info(self):
	    print('shark')

obj_goldfish=Fish()
obj_hammerhead=Shark()
obj_goldfish.info()
obj_hammerhead.info()
```
## OUTPUT
![image](https://github.com/user-attachments/assets/47f60c22-5e5c-403e-9e2f-dd655b87b840)

## RESULT
Thus the program has been successfully executed. 
