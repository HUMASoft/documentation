Requirements
============


device cia 402
--------------

must be able to:

 - set control mode Done
 - set speed Done
 - get speed Done -> Revision
 - set position Done
 - get position Done
 - set torque Done -> Revision
 - get torque Done -> Revision
 - check status Done -> Revision
 - init Done -> Revision
 - stop Done -> Revision
 - display errors ToDo
 - react to errors ToDo


robot
-----

joint
-----
must be able to:

 - be set in constructor
    - gear ratio
    - max-min pos, vel, acc.
 - get position from min to max
 - get speed from min to max
 - get torque from min to max
 - set position from min to max
 - set speed from min to max
 - set torque from min to max
 - have different callback controllers

