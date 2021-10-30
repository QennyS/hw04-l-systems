# Homework 4: L-systems

## Results
![Image1](https://github.com/QennyS/hw04-l-systems/blob/master/result.png)  \
Live link: https://qennys.github.io/hw04-l-systems/ \
Name: Yilei Li PennKey: 47053708

## Description
This project is to implement the L-System.

I also implmented a dusty, orange background by fbm noise function to incorporate the autumn theme.

### Drawing Rules
- `F`:  scale down a little bit, expand forward
- `L`: c
- `+`: rotate positively around Z axis

 drawing rules used to interpret the expanded axiom: "F" -> Scale our current Turtle down by a small amount, move forward, and create a Branch. "L" -> Create a Leaf at our current Turtle's position. "[" -> Push our current Turtle onto the stack. "]" -> Pop a new Turtle from our stack. "+" -> Rotate our current Turtle a positve amount around the forward axis. The amount is the specified angle plus a small randomly determined offset. "=" -> Rotate our current Turtle a positive amount around the up axis. "~" -> Rotate our current Turtle a positive amount around the right axis. "-" -> Rotate our current Turtle a negative amount around the forward axis. "_" -> Rotate our current Turtle a negative amount around the up axis. "*" -> Rotate our current Turtle a negative amount around the right axis.


## Controls
- `Iterations`: change the number of iterations in L-System
- `Angle`: change the angle in L-System
- `leaves_color`: change the color of leaves

## Sources
- [Online L-system renderer](http://www.kevs3d.co.uk/dev/lsystems/)
- [Algorithm of L-system](http://algorithmicbotany.org/papers/abop/abop-ch1.pdf)
