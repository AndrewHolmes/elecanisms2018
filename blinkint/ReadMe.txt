Project Title

	This project is an introduction to working with the PIC24 micro controller. After installing all necessary software I modified the blink.c file provided by the course instructors such that pressing a connected button would turn on an LED on the micro controller. 

Prerequisites

	You will need to have downloaded and installed all of the tools outlined in Handout 1.1

	a) The microchip compiler
	b) The SCONS build automation tool
	c) Fork the Github repository for Elecanisms 2018 and follow the instructions in the ReadMe in the bootloader folder to configure the boot-loader for your operating system.

Setup

	a) Connect the button to power and ground. 
	b) Use a pull-down resistor to bring the signal down to about zero volts when there is no active signal. I used a 110 Ohm resistor. 
	c) Connect a pin between the button and the pull-down resistor and to D2 on the micro controller. 



