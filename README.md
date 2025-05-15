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
~~~python
import math

class saveetha:
    @staticmethod
    def slot(radius):
        area = math.pi * (radius ** 2)
        return area

try:
    radius = float(input())
    if radius < 0:
        print("Radius cannot be negative.")
    else:
        result = saveetha.slot(radius)
        print(f"Area of circle: {result:.2f}")
except ValueError:
    print("Invalid input. Please enter a numeric value.")
~~~

## Output

![image](https://github.com/user-attachments/assets/31087e1f-1c67-4e00-a53c-c6db9936b03e)

## Result
Thus,the program has been executed successfully.
