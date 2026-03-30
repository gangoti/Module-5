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

```
class Fruits:
# Calling constructor
    def __init__(self):
        print('Fruits created.')
# Calling destructor
    def __del__(self):
        print('Destructor called, Fruits deleted.')
obj = Fruits()
del obj

```

### OUTPUT
<img width="1101" height="218" alt="438236431-96d5bec8-a4dc-48ab-88dc-b840b23d03ac" src="https://github.com/user-attachments/assets/b71806f7-c3c4-4442-917d-fea87c475efc" />


### RESULT
The program successfully adds two numbers using a parameterized constructor and deletes the instance using a destructor.
