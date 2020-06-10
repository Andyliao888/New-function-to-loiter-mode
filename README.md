# New-function-to-loiter-mode

Note: I compile the promgram in Qtcreator in ubuntu 16.04


I want to add new function to loiter mode.
First, when the quadcopter takes off,I want the quadcopter to reach height 5 m.
Second, after the height reached height 5 m , I want quadcopter to land.

According to these,I have add a new variable called AltHold_LandforHeight in line 124 in mode.h and alse add a statement in line 783  in mode.cpp.
Finally, I use the function called landing_with_GPS from line 183 to line 185 in mode_loiter.cpp
