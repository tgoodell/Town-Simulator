# Town-Simulator
Programming challenge. Given the API documentation for a simulation of a town, define a method, travel(), for a corresponding class,
Vehicle, that will navigate the town, seeking a target location randomly selected by the simulator at run time.

# API Documentation
## Class: Simulator
### Methods:
**public String get_location()**
  Returns current location of vehicle as a String.
**public String get_goal()**
  Returns target location set at run time as a String.
**public String look_ahead(String direction)**
  Takes as an argument a cardinal direction: NORTH, SOUTH, EAST, WEST. Returns the location one step ahead as a String.
**public void drive(String direction)**
  Accepts as an argument a cardinal direction: NORTH, SOUTH, EAST, WEST. Moves the vehicle in the direction indicated in the 
  argument.

