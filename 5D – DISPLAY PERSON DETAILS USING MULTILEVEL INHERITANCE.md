# Experiment No: 5d – Display Person Details Using Multilevel Inheritance

## AIM  
To write a Python program to get the name, age, and ID of a person and display the details using multilevel inheritance.

---

## ALGORITHM  
1. Define the base class `work` with a constructor to initialize the `name`.
2. Define a derived class `Employee` inheriting from `work`, with an additional parameter `age`.
3. Define another derived class `Salary` inheriting from `Employee`, with an additional parameter `salary/id`.
4. Include a `disp()` method in `Salary` to print the name, age, and salary/id.
5. Get user input for name, age, and id.
6. Create an instance of the `Salary` class.
7. Call the `disp()` method to display the result.
8. Terminate the program.

---

## 🧾 PROGRAM

```python
class work:
    def __init__(self, name):
        self.name = name

class Employee(work):
    def __init__(self, name, age):
        super().__init__(name)
        self.age = age

class Salary(Employee):
    def __init__(self, name, age, salary):
        super().__init__(name, age)
        self.salary = salary

    def disp(self):
        print(f"{self.name} {self.age} {self.salary}")

name = input()
age = int(input())
salary = int(input())

person = Salary(name, age, salary)
person.disp()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/eb76b846-239d-4f45-82b7-f9faf3656eff)

### RESULT
Thus, the Python program to display the details of a person using multilevel inheritance has been executed successfully.
