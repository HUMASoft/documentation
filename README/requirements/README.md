Requirements
============


device cia 402
--------------

must be able to:
 - set control mode Done->Revision
 - set speed ToDo
 - get speed ToDo
 - set position Done->Revision
 - get position Done-Revision
 - set torque ToDo
 - get torque ToDo
 - check status Done->Revision
 - init Done->Revision
 - stop Done->Revision
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

ciaIcan
-------
must be able to:
  - convert cia402 msg from cia devices to can msg
  - send canmsg trough canbus device
