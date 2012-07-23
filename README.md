# Wall Proto

Programs in MIT Proto for running on the wall.

I could not get this to run with the neocompiler, so I am using the protocompiler

The protocompiler has several bugs:
* incorrect use of pi instead of (pi) in toDegrees and toRadians
* (dt) seems to be numerically unstable and quickly becomes a constant (probably 1)