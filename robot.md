
# Requirements
1. Robot with two motors
2. Motor board
3. Connector wires 
4. Raspberry Pi Zero, screen, keyboard, mouse and adaptors to make it all work


# Controlling a motor:
1. Set up Pi Zero with screen, keyboard and mouse
2. Turn everything on
3. Open up Python3 IDE
4. Create a new file by clicking on File > New File. Save your new file as motor_test.py.
5. Check [Pi GPIO Schematic](https://www.raspberrypi.org/documentation/usage/gpio-plus-and-raspi2) to be sure of numbers
6. First let's control the motors individually
7. Here is some code to try - check the numbers that the wires are connected to...

```python
from gpiozero import Motor
from time import sleep

motor = Motor(5, 6)

motor.forwards()
sleep(1)
motor.stop()
sleep(1)
motor.backward()
sleep()

```
8. Save the file 
9. Run the file using Run module. 




# Controlling both motors of the robot

If you want to control both motors simultaneously, then you can use the Robot class. For example:

``` python
from gpiozero import Robot
from time import sleep
robot = Robot(left = (5, 6), right = (16, 21))

robot.forward()
sleep(1)
robot.stop()
robot.right(0.5)
sleep(1)
robot.backward()
sleep(1)
robot.stop()
```


Adapted from: https://projects.raspberrypi.org/en/projects/build-a-buggy/
