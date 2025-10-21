# in-class-activities
## Devlogs
### W1
"Hello world!"

### W2

The variables r, g and b are floats because there are fractional numbers not base 10 numbers.
The _bounce variable an int instead of a float, bool, or string beacuse _bounce is a whole number. 
The error that I got after step 4 was a "missing semicolon". This reminds me that is import not to forgot the ";" at the end of each code to be able to run it.

### W3

Part 1#
We make the parameter "friendship level = 0%-100%" and the return type (output) "type boolean = True(yes secret)/false(no secreat)".

Part 2#

1# Classes are used to implement/create components the metaphor that we create is "classes are like the ingredients of a plate. For example, classes can be the egg, or cake batter. And component is the cake"

2# We think the balls get extremely bright if they bounce
too much beacuse each time they bounce the ball color multiplier
is applied making the values higher and in turn making the color
brighter.

### W4
1:
In line number 5, it seems that a new variable called _moveSpeed of type float (decimal) is being created. The assigned value is "1.0f". In line 22, a new variable called 'translation' is being created, which gets as its value the multiplication of three elements: Input.GetAxis("Vertical"), _moveSpeed, and Time.deltaTime. I only recognize two of them: the element _moveSpeed, which is the variable created in line 5 that represents the speed of movement, and Time.deltaTime, which is responsible for showing how time changes as the game progresses. I don't understand line 25 very well, but it seems that a method is being called along with "transform" to transform the variable created in line 22.

2:
The decisions I made were to add Rigidbodies to the cat and the ball because I needed them to be able to move around the game without falling. In the case of the ball, I needed this because it needs to bounce and move naturally around the area. For the goal, I checked Is Trigger On because it doesn't need to move.


### a flag is the same as booleans.

## Open-Source Assets

- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
