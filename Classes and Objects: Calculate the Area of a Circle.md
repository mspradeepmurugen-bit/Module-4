# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

# Step 2: Define the class
class cse:
    # Step 3: Define the method
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)

# Step 1: Get user input
radius = float(input("Enter the radius of the circle: "))

# Step 4: Create object and call method
obj = cse()
obj.mech(radius)
```

## Output
<img width="987" height="313" alt="Screenshot 2025-12-28 143612" src="https://github.com/user-attachments/assets/e25aacfe-5460-4a49-9ad3-9a66521bc138" />

## Result
thus the python program is executed sucessfully!
