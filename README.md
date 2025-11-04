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

### W5

1) 
I thought the method to activate a Vector3 would have to be start(), but it seems to be update(). Can you use a Start() method together with an update() to activate it from the beginning?
A: yes you can and often should use both Start()[for continuous behavior] and Update()[for initial setup] together

(I was not present in class, but I thought of a question and researched it. I hope this is correct.)

2) 
I think that in this activity, the member variables we might need include one to set the speed at which the deer will move, and another one for the Transform but I'm not sure how to declare this.
The method this class should probably have is Start(), because the deer is supposed to move as soon as the player presses start.
Maybe also an Update(), but I’m not completely sure, since the instructions don’t say that the action should be repeated multiple times.

## W6

My catagory assign is (Math)
https://docs.google.com/document/d/1O1Z4J196hUgrUu8E1KjuXLG0qGOnDDlSYW_Ya_sPJhE/edit?usp=sharing 


- Speed variable. 
- Enable() method to stop the bats movement.  
- We would need to use a for-loop to attach all of the bath to the catplayer and for   the loop we would definitely use Update() to run the code multiple times and definitely the Start() method but I’m unsure were maybe for make the bat chase the player since  the beginning .
- We need to make the variables with this [SerializeField]
  at the beginning.


### a flag is the same as booleans.

## Open-Source Assets

- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
