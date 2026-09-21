# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```python

class Student:
  
    def __init__(self):
        print("Inside Constructor")
        print("Object initialized")
        self.name = "Emma"
        print(f"Hello, my name is {self.name}")

    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")

s2 = Student()

del s2


```
### OUTPUT
<img width="597" height="234" alt="image" src="https://github.com/user-attachments/assets/d6f0edaa-e245-4460-95ab-4c45313d6491" />


### RESULT
Thus the python program to create a Python class `Student` with a destructor has been implemented and executed successfully.
