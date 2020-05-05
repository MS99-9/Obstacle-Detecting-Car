# Obstacle-Detecting-Car
 Project link : https://drive.google.com/file/d/15fe8V1CIQqSKYeXQzsCRBJrqOju35XQ0/view
Description :
The project is all about a car that moves in one direction and it has two sensors .The first is a motion sensor, by switching the switch on this sensor detects the input and outputs the movement of the car .The second sensor is infra-red sensor ,which detects any obstacle infant of the moving car and when it finds an obstacle ,it stops and a LED lights .
Components:
LED 5 gn_dif: lighting
Super Glue: assembling
Protoboard 400: linking between the FPGA and component IR sensor: detecting obstacles
FlexJumper 20M/F -10x: connection
FlexJumper 20F/F -10x: connection
L298N Dual Bridge DC Stepper Controll: motor coordination 2 Wheel Drive Motor Chassis Robotics: motion
Beginner Soldering Kit Flashlight: car modelling
Inputs Taken :
2 inputs , the IR signal and fpga switch, the IR input we modelled it as a 1bit input in our software , the second input was handeled also as a 1bit input in our code
Outputs Configured:
2 outputs , the car motion and the LED lamp, we modelled the car motion as 4 bit outputs in our software each of them controlling the direction of the motion of the motors, the lighting of the lamp was modelled as a 1 bit output in our software on/off
Problems:
1- how to make quartis read our code as the top hierarchy instead of the default golden top file 2- how to merge the 2 modules, the car and IR, into a single coherent module
Limitations:
1- faced a problem relating the rotation of the wheel
2- managing the voltage distributions among the components as they had different voltage requirements
