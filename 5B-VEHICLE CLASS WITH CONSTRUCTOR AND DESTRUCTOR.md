# Experiment No: 5b-Vehicle Class with Constructor and Destructor

## AIM  
To create a Python class `Vehicle` that has a constructor (`__init__`) and a destructor (`__del__`). We will create an instance of the class and delete it right after.

---

## ALGORITHM  
1. Begin the program.  
2. Define a class `vehicle` with the constructor `__init__(self)` to print "Vehicle created." when an object is instantiated.
3. Define a destructor `__del__(self)` to print "Destructor called, vehicle deleted." when the object is deleted.
4. Create an instance of the `vehicle` class.
5. The destructor will be automatically called when the object goes out of scope or is explicitly deleted.
6. Terminate the program.

---

## 🧾 PROGRAM

```python
class vehicle:
    def __init__(self):
        print("Vehicle created.")
    
    def __del__(self):
        print("Destructor called, vehicle deleted.")

v = vehicle()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/b2d98b07-a507-4788-ad43-67abc83800b4)

### RESULT
Thus, the Python program to create a vehicle class with a constructor and destructor has been implemented and executed successfully.
