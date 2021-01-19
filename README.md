# MESC
High power ESC using VESC logic

MIGHTY VESC (MESC) - HIGH POWER INVERTERS RUNNING VESC® SOFTWARE

MESC is my first generation controller. It was designed to be used in light to medium vehicles running at low voltages.
Pair it with a powerful motor and battery supplying enough juice and it is perfect for your DIY EV conversion project.

MESC - G1 specs
144V max supply voltage 
800A max phase current
Phase current sensors (hall)
72x IPT059N15N3 150V MOSFET


This monstrosity is a 72 FET design. It uses 150V PG-HSOF-8 mosfets and is designed for input voltages up to 144V. 
It's primary use case are light and medium duty electric vehicles. It features integrated  high efficiency 12V 5A dcdc power supply and custom input connectors
to ensure easy throttle connection. I'm using hall current sensors - similar design as electric cars.
It was designed up to 800A phase current but we'll see about that. PCB is standard thickness 4 layer board. Busbars soldered on bottom and top carry high current.
The board is also ready for high voltage modification. With suitable capacitors and mosfets it is possible to turn this board into higher voltage / lower current
controller up to 150V input voltage.

MESC Hardware is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/.
