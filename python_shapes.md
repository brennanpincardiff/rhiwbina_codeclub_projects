# Welcome to Code Club. 
# Today we want to have fun making some shapes in python. 

Go to [https://trinket.io/]

We're going to use a python library called turtle.
Lots of documentation here: https://docs.python.org/3/library/turtle.html

Start by typing in this code:
``` python
from turtle import *
```

Then type this code to make a square using a loop. 
``` python
for i in range (1,5):
  forward(100)
  right(90)
```
Run the code by pressing the triangle button.

Let's make a hexagon:
``` python
n = 5
for i in range(n):
  forward(100)
  right(360/n)
```
Run the code by pressing the triangle button.

We can have more fun by creating a variable called side and altering this in the loop. 
Here is the code.
``` python
# hexagon fun
side = 100
for i in range(104):
  forward(side)
  right(72) #Exterior angle of a pentagon is 72 degree
  side = side - 2
```
Run the code by pressing the triangle button.

You can also change the speed and the colour to make this spiral. 
``` python
#sprial fun
speed(0)
for i in range(200):
  color("red")
  forward(i * 2)  # double size
  right(121)  # 120 degrees is an equilateral triangle
```
Run the code by pressing the triangle button.

I hope you've enjoyed writing some python code. 
You've done a great job and learned about loops and variables. 
Well done. 
For more python tutorials, go to: https://projects.raspberrypi.org/en/projects/



