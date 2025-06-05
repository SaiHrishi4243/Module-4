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

```python

import math
class cse:
    def mech(r):
        area=math.pi*(r**2)
        print(area)
a=int(input("Enter Radius of Circle :"))
cse.mech(a)

```

## Output

![image](https://github.com/user-attachments/assets/36a6ea32-4b1a-4f4c-9a3f-0c5404a4ea01)

## Result

Thus implemented the python program to claculate the area of a circle based on the redius provided by the user.
