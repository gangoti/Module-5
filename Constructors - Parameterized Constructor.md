# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class Addition:
    first = 0
    second = 0
    answer = 0
     
    # parameterized constructor
    def __init__(self, f, s):
        self.first = f
        self.second = s
     
    def display(self):
        print("First number = " + str(self.first))
        print("Second number = " + str(self.second))
        print("Addition of two numbers = " + str(self.answer))
 
    def calculate(self):
        self.answer = self.first + self.second
 
# creating object of the class
# this will invoke parameterize constructor
x=int(input())
y=int(input())

obj = Addition(x,y)
 
# perform Addition
obj.calculate()
 
# display result
obj.display()



```

### OUTPUT
<img width="1093" height="334" alt="438234322-8468e4d2-0020-4935-8258-8a37f3e907f8" src="https://github.com/user-attachments/assets/432bc5b7-8835-49fc-a886-27295d65e0b9" />

### RESULT

The program successfully performs the addition of two numbers using a class with a parameterized constructor and displays the result.

