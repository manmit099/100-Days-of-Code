# Hurdle Challenge Using While Loops

## Hurdle 3

[Reeborg's World](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%203&url=worlds%2Ftutorial_en%2Fhurdle3.json)

```python
def turn_right():
    turn_left()
    turn_left()
    turn_left()
def jump():
    move()
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
while not at_goal(): 
# not True is false and not False is True.
# see it as a whole (not at_goal()), if it is true then loop continues 
    if front_is_clear():
        move()
    else:
        jump()

```

```python
while at_goal() != True:
    if front_is_clear():
        move()    
    else:       
        jump()

```