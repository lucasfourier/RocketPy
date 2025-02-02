Code Documentation
==================

RocketPy's code is fairly well documented. The code is structured into 5 main classes:

 - Function: a helper class to facilitate mathematical manipulation, interpolation and plotting of data resultinf from experiments or simulation.
 - Environment: a class that takes care of atmospheric properties and other environment related variables pertinent to flight simulation.
 - SolidMotor: a class to model solid rocket motors and process them to be assigned to a rocket.
 - Rocket: a class that holds all properties related to a rocket, such as its inertia properties, motor, aerodynamic surfaces and parachutes.
 - Flight: the class that takes the rocket and the environment and actually perform the flight simulation, post-processing the results.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   classes/Function
   classes/Environment
   classes/SolidMotor
   classes/Rocket
   classes/Flight
