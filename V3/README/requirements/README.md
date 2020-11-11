

Requirements
============

The new neck design must perform all the movements available in the old version.


Functionalities in the old versions
===================================


device cia 402
--------------

Current library is able to:

 - set control mode
 - set speed
 - get speed
 - set position
 - get position
 - set torque
 - get torque
 - check status
 - init Done
 - stop Done
 - display errors (in python)
 - react to errors ToDo

Find more information in :

  * [Library](https://github.com/HUMASoft/CiA402Device)
  * [Examples](https://github.com/HUMASoft/CiA402Device-examples)


Additional classes created
--------------------------

A class allowing to define different device parameters has been created and passed as a parameter when the CiA402 objects are instatiated. This enables to use the same library with the new versions of the neck.
