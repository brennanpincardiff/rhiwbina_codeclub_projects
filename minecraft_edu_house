# Welcome to Code Club. 
## Today we want to make a house in Minecraft Education... 

### Step 1: a flat world
Open a flat world in minecraft education. I also advise using creative mode. 
Maybe turn on co-ordinates, turn off day/night cycle and turn off weather too but it's your choice. 

You can use blocks or python. Python will be more useful for the future. 


### Step 2: create a big cube of blocks
Here is the python code to put into the code window
``` python
def on_on_chat():
    blocks.fill(GRASS, pos(1, -1, 1), pos(11, 11, 11), FillOperation.REPLACE)
player.on_chat("house", on_on_chat)

```
Test this by closing the code and typing house in the text box (press t to get a text box)


### Step 3: hollow cube
This will build a big full block, make it hollow:

``` python
def on_on_chat():
    blocks.fill(GRASS, pos(1, -1, 1), pos(11, 11, 11), FillOperation.HOLLOW)
player.on_chat("house", on_on_chat)

```

### Step 4: play to make different houses
You can change what the house is made of. Try:
- STONE
- WOOL
- RED_WOOL


### Step 5: add a window and a hole for a door. 
Let's try adding a <b>window</b>. Try adding this to the code just under the blocks.fill command.
``` python
blocks.fill(GLASS, pos(1, 3, 2), pos(1, 6, 8), FillOperation.REPLACE)
```
Play with the position and size of the window. Maybe add more than one window to different walls. 


And a hole for a door... 
``` python
blocks.fill(AIR, pos(1, 0, 5), pos(1, 1, 7), FillOperation.REPLACE)
```


So in total the final code looks like this:
``` python
def on_on_chat():
    blocks.fill(STONE,
        pos(1, -1, 1),
        pos(11, 11, 11),
        FillOperation.HOLLOW)
    blocks.fill(GLASS, pos(1, 3, 2), pos(1, 6, 8), FillOperation.REPLACE)
    blocks.fill(AIR, pos(1, 0, 5), pos(1, 1, 7), FillOperation.REPLACE)
 
player.on_chat("house", on_on_chat)
``` 








Adapated from this YouTube lesson: https://www.youtube.com/watch?v=APSo9qFngoM

