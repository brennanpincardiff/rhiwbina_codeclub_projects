# Welcome to Code Club. 
## Today we want to make a collection of houses in Minecraft Education... 

### Step 1: a flat world
Open a flat world in minecraft education. I also advise using creative mode. 
Maybe turn on co-ordinates, turn off day/night cycle and turn off weather too but it's your choice. 

You can use blocks or python. Python will be more useful for the future. 


### Step 1: make two houses
Here is the python code to put into the code window
``` python
def house(x=1):
    blocks.fill(YELLOW_CONCRETE,
        pos(x, -1, 1),
        pos(x+10, 11, 11),
        FillOperation.HOLLOW)
    blocks.fill(GLASS, pos(x, 3, 2), pos(x, 6, 8), FillOperation.REPLACE)
    blocks.fill(AIR, pos(x, 0, 5), pos(x, 1, 7), FillOperation.REPLACE)
 
def build_2_houses():
    house(x=1)
    house(x=15)

player.on_chat("2 houses", build_2_houses)

```

These don't feel quite right in terms of orientation but it's a start...

