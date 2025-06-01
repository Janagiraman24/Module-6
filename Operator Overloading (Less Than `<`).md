# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class saveetha:
    def __init__(self,val):
        self.val=val
    def __gt__(self,other):
        return self.val<other.val
ob1=saveetha(90)
ob2=saveetha(80)
print(ob1<ob2)
```
## Output
![image](https://github.com/user-attachments/assets/58c304ef-1156-47c7-b8ac-86a4879130c0)

## Result
Thus  the program has been successfully executed.
