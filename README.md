# Twisty
A twisty way of representing maths. Looks nice too.

## How to
Pressing 'V' toggles the UI to make it visually clean\
Pressing Space updates the stack with new values put in the input fields

## For the formula:
I have no idea the limits of what it can do, and I'm sure its very easy to crash this program. It is using the [Mathos Expression Parser](https://github.com/MathosProject/Mathos-Parser), so maybe that can clue you in as to its limits. The string 'stickNum' (capital 'N') is used as the variable for how high the stick is, with 0 being the lowest stick in the stack, and the highest being the predefined number of sticks - 1. Sin Cos etc functions are done in radians, and pi is a constant that can be used.

## Formula Examples
`stickNum/15`\
`stickNum^2/400`\
`sin((stickNum*10)*(pi/180))`
