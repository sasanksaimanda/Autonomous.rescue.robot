# Autonomous.rescue.robot
This is a project made for rescuing in situations which are very dangerous for human rescue team to entering field like in time of natural calamities and disaster events
This project was made with aurdino uno model

BRIEF:

INTRODUCTION:-  A Passive Infrared sensor is used in the project which emits infrared rays to detect humans. As live human body emits thermal radiation it is received and manipulated by the PIR sensor to detect humans. Once the people are located it immediately gives audio alert visual alerts to the authorities so that help can reach the live person very fast. This PIR sensor is placed on a moving all direction robot that can move in the earthquake prone areas. The robot is driven on a geared dc motor for increased torque and low speed and stepper motor for increased turning accuracy hence the precise control of position is monitored. The robot consists of a three wheel geared drive with DC motors attached to perform forward and reverse movement. Detection by rescue workers is time consuming; therefore here we are using the robot for earthquake recue operation. 

Microcontroller:- 
 PIC16F877A is the microcontroller used in this system. Signals from PIR sensors are given to the microcontroller and this microcontroller will digitize the signal and send it to the zigbee. The controller has features like inbuilt ADC, required to get the signals from the various sensors. Beside this the microcontroller that is used in this project has some additional advantages. 

ZIGBEE Transceiver:-  
It is used to send and receive data between robot and the control unit. Zigbee is a digital wireless communication protocol. It is a very low power communication technology.  

Motor and motor drive:-  
Motor denotes the robot which can move over earthquake prone areas. Motor drive is the interfacing circuit between microcontroller and robot. The project uses DC motor. DC motors have polarity and direction of rotation depends on direction of current. But a DC motor cannot be interfaced to the microcontroller directly because it requires much higher voltage and current. Motor drive is used for this. It is built using an npn transistor –BC547. It acts as an interfacing device to supply required power to the motor.  

Voltage conversion circuit:- 
 The operating voltage of zigbee transceiver and PC are different hence we need a voltage conversion circuit. 

Image Report:- 
An optical image will be sent by the robot module to the control module which we can observe in the PC. 

Hence many lives can be saved by using this autonomous robot during an earthquake disaster in a short duration which becomes time consuming and unaffected if done manually. This robot can be improved by using high range sensors and high capacity motors. Some more sensors like mobile phone detector, metal detector etc. can be implemented to make this robot more effective. 
