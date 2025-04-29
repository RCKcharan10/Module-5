# Experiment No: 5a-Employee Class with Parameterized Constructor

## AIM  
To create a Python class `employee` with parameterized constructors with the parameters as `id` and `name`, and print the details of the employee using the `display(self)` method.

---

## ALGORITHM  
1. Begin the program.  
2. Define a class `employee` with a parameterized constructor that takes `id` and `name` as arguments.
3. Define a method `disp()` to display the employee's details.
4. Read input values for `id` and `name` from the user.
5. Create an instance of the `employee` class.
6. Call the `disp()` method to display the employee details.
7. Terminate the program.

---

## 🧾 PROGRAM

```python
class employee:
    def __init__(self, id, name):
        self.id = id
        self.name = name
    
    def disp(self):
        print(f"Hello my id is : {self.id}")
        print(f"My name is : {self.name}")

id = input()
name = input()
e = employee(id, name)
e.disp()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/8240db55-9930-4f09-85cc-ad108de592f9)

### RESULT
Thus, the Python program to create an employee class with parameterized constructor and display employee details has been implemented and executed successfully.
