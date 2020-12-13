# CLAP-cum-LDR-based-self-propelled-car

This  project is aimed towards building a model of a car which is self-propelled. This model consists of two specific circuits in which first circuit is CLAP switch circuit and the second one is a LDR based Dark mode circuit. Each of these circuits are connected with separate 9 V DC source. The LDR-Dark circuit is connected with a motor and headlight.

![Sociogram Home Page](https://github.com/GraniteMask/sociogram-1/blob/master/sociogram.png?raw=true)

## Abstract:

This project is aimed towards building a model of a car which is self-propelled. This model consists of two specific circuits in which first circuit is CLAP switch circuit and the second one is a LDR based Dark mode circuit. Each of these circuits are connected with separate 9 V DC source. The LDR-Dark circuit is connected with a motor and headlight. The motor is responsible for the rotation of the generator as well as the axle of the car. At first, we have to switch on the first switch which establishes the connection between 9 V DC source and the CLAP switch circuit. Then, we have to turn on the second switch which establishes the connection between another 9 V DC source with the LDR-Dark circuit. As soon as we turn on the second switch, the car starts moving. To stop the car we have to clap. The backlight also starts glowing when the car stops and headlight stops glowing.

## Motivation for the project:

1)	If any passenger wants to get off from a crowded bus at desired stop then that passenger can use this circuit (which is preinstalled in bus) by clapping to stop the bus.
2)	If some kind of requirement felt by any passenger to stop the train, then they can stop the train by pressing a switch (protected by a glass cover to protect from misuse) and then clapping to stop the train
3)	Same circuit can be used in industries to stop certain movements which require immediate and minute actions like while moving a weight from one place to another, if something wrong is going to happen the supervisor can stop the system by clapping only.

## Description of the project:

This project has two major circuits. First circuit has Clap mechanism in which we have to give sound as an input which would turn on the LED to trigger the LDR circuit (2nd circuit) as well as the backlight of the car. LDR circuit is used to drive the motor which in turn will drive the car as well as run the generator. In the Clap circuit we are using the BC547 and BC548 transistors. In the LDR circuit we are using BC547 transistor and 1N4007 diode.

## Circuit Diagram:

![Sociogram Home Page](https://github.com/GraniteMask/sociogram-1/blob/master/sociogram.png?raw=true)

## Components Required:

1.	Bread Board	1
2.	Mic Condenser	1
3.	Wires	As per requirement
4.	Dielectric Capacitor (100 µF)	2-3
5.	Resistance 
      	10K Ω - 4
      	220 Ω - 1
      	1M Ω	-  1

6. Transistor 
      	BC 547  -  2
      	BC 548	-  1
7.	Diode (1N4007)	1
8.	LDR 	1
9.	Motor	2
10.	LED	4
11.	Battery	2

The BC547 is a NPN silicon transistor is generally used as a current amplifier. It has a peak or maximum collector current rating of 200mA and power dissipation of 500mW.

The BC548 is a NPN silicon transistor which is also used as a current amplifier.it has same peak collector current rating and power dissipation value as the BC547.

The BC548 transistor and BC547 are essentially the same but BC547 has a higher breakdown voltage whereas BC548 has low noise.

1N4007 is a PN junction rectifier diode. These types of diodes allow only unidirectional flow of electrical current. So, it can be used to filter out any harmonics or disturbances created in the circuit by the running motor.

## Working principle of the project:

This model consists of two specific circuits in which first circuit is CLAP switch circuit and the second one is a LDR based circuit. Each of these circuits is connected with separate 9 V DC source.
The LDR circuit is connected with a motor and headlight. The motor is responsible for the rotation of the generator as well as the axle of the car. Axle of the car is connected with the motor using two pulleys, one with axle and another with the motor and interconnected with a rubber band. The generator is directly coupled to the prime motor and can be used to generate power which can be later used.
At first, we have to turn on the first switch which establishes the connection between 9 V DC source and the CLAP switch circuit. Then, we have to turn on the second switch which establishes the connection between another 9 V DC sources with the LDR-Dark circuit.
As soon as we turn on the second switch, the car starts moving and the headlight starts glowing. To stop the car we have to clap. The backlight also starts glowing when the car stops and headlight stops glowing.

## Future Scopes:

Same circuit can be used in industries to stop certain movements which requires immediate and minute actions like while moving a weight from one place to another, if something wrong is going to happen the supervisor can stop the system by clapping only.
