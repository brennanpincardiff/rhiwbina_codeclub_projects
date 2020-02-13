# Welcome to Code Club. 
## Building on python shapes - add some colour

Go to [https://trinket.io/]

Need to understand RGB colour. 
R, G, B corresponds to Red, Green and Blue

### Draw a turtle. 
``` python
from turtle import *
shape("turtle")
```
Run the code by pressing the triangle button.


### Colour the turtle. 
``` python
from turtle import *
color(150, 150, 150)
shape("turtle")
```
It should be grey. 
Try making it red, green and blue

### Draw a spiral with various colours
``` python
from turtle import *
#sprial fun
speed(0)
for i in range(200):
  color(i,0,0)
  forward(i * 2)  # double size
  right(121)  # 120 degrees is an equilateral triangle
  
```

Run the code by pressing the triangle button. 

Well done. 

For more python tutorials, go to: https://projects.raspberrypi.org/en/projects/

Turtle documentation here: https://docs.python.org/3/library/turtle.html
