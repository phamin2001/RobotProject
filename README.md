Our project is to build an automaton, a little program that performs a task in a virtual world. Our automaton will be a mail-delivery robot picking up and dropping off parcels.

There’s the robot’s current location and the collection of undelivered parcels, each of which has a current location and a destination address. That’s it.
And while we’re at it, let’s make it so that we don’t change this state when the robot moves but rather compute a new state for the situation after the move.

