# Infrared-light-position-based-headtracker
Infrared light based headtracker using 2d position tracking to infer 3d head position.
- it allows for 3d head position to be used for computer input

It tracks the 2d position of 3 IR led's in order to calculate the 3d position of your head.

One of the issues was how to prevent the batteries from permamently damaging themselves from overdischarge. This was fixed by a use of an op-amp to act as cut-off logic once voltage reaches bellow a certain threshold.

The head tracker managed to reliably track the position of user's head.
