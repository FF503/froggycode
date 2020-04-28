==============
Robot Hardware
==============

Base Class
~~~~~~~~~~

The base RobotHardware class should only be used to assign variables which are deemed to be universal across all robots. Any robot-specific variables should be declared
but do not need to be assigned values. The default value of unassigned integers will be 0.

Specific RobotHardware classes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Due to hardware differences between individual robots (i.e. practice, programming, and comp bots), specific classes extending from RobotHardware should be written for
each unique robot. No new variables should be declared; rather, in the initialize() function, all relevant robot-specific variables should be assigned.
