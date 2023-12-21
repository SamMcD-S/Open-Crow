# Open-Crow
Open-Crow is an open source proof of concept for a Voltage Glitch Attack. The first version of the project was designed to run on the Digilent Basys 3 FPGA Development board.

The top level module for this project is only responsible for configuring the parameters of the attack, and should be easy to modify (or exchange).

The glitch attack controller, implemented as a Finite State Machine triggers an attack on each rising edge of the trigger signal, as long as the enable input is asserted.


