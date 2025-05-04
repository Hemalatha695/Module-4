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
Add code here
```
import math  # For the value of pi

# Step 2: Define the class
class cse:
    
    # Step 3: Define the method 'mech' to calculate area
    def mech(self, r):
        area = math.pi * r * r
        print(f"The area of the circle with radius {r} is: {area:.2f}")

# Step 1: Get user input
radius = float(input("Enter the radius of the circle: "))

# Step 4: Create an object of the class and call the method
obj = cse()
obj.mech(radius)
```
## Output
```
The area of the circle with radius 7.0 is: 153.94
```
## Result
This program successfully encapsulates the area calculation in a class method and interacts with the user for input. 
