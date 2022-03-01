# CMOS Implementation of Strong Arm Comparator Latch
This repository represents the CMOS implementation of a Comparator circuit with an RS Latch. The circuit was built using Synopsys Custom Compiler tool on a 28nm Technology.
## Contents
### 1. Abstract
### 2. Tools Used
### 3. Schematic
### 4. Detailed working of the circuit
### 5. Simulation Analysis
### 6. Netlist
### 7. Acknowledgements
### 8. Reference

## 1. Abstract
Comparators form the basic building blocks in various circuits such as ADCs. The scope of this project is to design a comparator with an output SR Latch to latch the outputs obtained to fixed values. A comparator senses a differential input and generates a logical output according to the polarity of the input difference. Here, a Strong Arm Latch has been selected as the comparator core. This topology offers desirable attributes like operating in a single clock phase, drawing zero static power.

## 2. Tools used
1. **Synopsys Custom Compiler** was used to draw the transistor level schematic diagram of the design.
  
2. **Synopsys PrimeSim** was used to plot the resultant transient analysis waveforms.

## 3. Schematic

![schematic1](https://user-images.githubusercontent.com/100681789/156213491-adc00e85-9e33-4a70-9201-00b9eaedbab1.PNG)
> Fig 1: Schematic of Comparator

![schematic2](https://user-images.githubusercontent.com/100681789/156206359-f38b6700-60f2-44f6-9794-ddf01f09b55a.PNG)
> Fig 2: Schematic of SR Latch

## 4. Detailed working of the circuit

## 5. Simulation Analysis
A pulse wave of 1GHz was set as the circuit clock. The circuit Vdd was given as 1.05V. A constant voltage of 0.5V was supplied at input terminal 2. A varying voltage source was given in terminal 1. 

![waveforms](https://user-images.githubusercontent.com/100681789/156207907-844ddd40-1cc0-4f32-b97b-2c1701eb217c.PNG)
> Fig 3: Simulation Wave forms

***1. Delay:*** Delay of the circuit is obtained as 0.2 ns. It is clear from the comparison between waveforms CLK high and output A switch.

![Delay](https://user-images.githubusercontent.com/100681789/156210610-aad99c10-26e4-46df-8c07-4ae13edc2e2b.PNG)
> Fig 4: Delay of circuit

***2. Offset Voltage*** There was no offset voltage observed. Similiar inputs were given on both the input terminals and the output was observed. There were no significant voltages variations observed at the output.

## 6. Netlist
Attaching is the final netlist of the design here:  [netlist.txt](https://github.com/Reshma-SM/CMOS-Implementation-of-Strong-Arm-Comparator-Latch/files/8163446/netlist.txt)


## 7. Acknowledgements
I express my special thanks to Kunal Ghosh, the Co-Founder of VLSI System Design, Corp. Pvt. Ltd. for coordinating this event and making it a grand success. I have acheived a great amount of knowledge by participating in this event. Thank you Chinmay panda and Sameer Durgoji for the quick guidance and support. I would also like to extend my sincere gratitude to Synopsys India, for making this event possible. Lastly, thanking IIT Hyderabad for this oppurtunity.

## 8. Reference
[1]	B. Razavi, "The StrongARM Latch [A Circuit for All Seasons]," in IEEE Solid-State Circuits Magazine, vol. 7, no. 2, pp. 12-17, Spring 2015, doi: 10.1109/MSSC.2015.2418155.H. Simpson, Dumb Robots, 3rd ed., Springfield: UOS Press, 2004, pp.6-9.

[2]	B. Razavi, "The Design of a Comparator [The Analog Mind]," in IEEE Solid-State Circuits Magazine, vol. 12, no. 4, pp. 8-14, Fall 2020, doi: 10.1109/MSSC.2020.3021865.
