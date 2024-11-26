# MK8 Ford Cluster

## Pinout 

12V+ - PIN 8

GND - PIN 3

FUEL LVL - PIN 10

FUEL LVL RETURN - PIN 2

CANH - PIN 12

CANL - PIN 13


## Fuel

Fuel level is determined by the resistance between fuel lvl and fuel lvl return pins.

Connect a 10 ohm resistor to display full fuel (this is a four band resistor with the following properties: Band #1 Brown, Band #2 Black, Multiplier #3 Black, Tolerance #4 Gold)

An 180 ohm resistor will display empty fuel (default if no resistor is connected).

Values in between 10 <-> 180 will display differing fuel levels.
