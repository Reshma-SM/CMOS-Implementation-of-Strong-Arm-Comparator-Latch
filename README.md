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
![schematic1](https://user-images.githubusercontent.com/100681789/156205522-f48f84fb-8053-4612-a2f7-552bcb79c722.PNG)
> Fig 1: Schematic of Comparator

![schematic2](https://user-images.githubusercontent.com/100681789/156205674-27aadd9d-e23e-4ce7-a8c8-981f87ce633c.PNG)
> Fig 2: Schematic of SR Latch

## 4. Detailed working of the circuit

## 5. Simulation Analysis

## 6. Netlist
Attaching is the final netlist of the design here:  

## 7. Acknowledgements
I express my special thanks to Kunal Ghosh, the Co-Founder of VLSI System Design, Corp. Pvt. Ltd. for coordinating this event and making it a grand success. I have acheived a great amount of knowledge by participating in this event. Thank you Chinmay panda and Sameer Durgoji for the quick guidance and support. I would also like to extend my sincere gratitude to Synopsys India, for making this event possible. Lastly, thanking IIT Hyderabad for this oppurtunity.

## 8. Reference
[1]	B. Razavi, "The StrongARM Latch [A Circuit for All Seasons]," in IEEE Solid-State Circuits Magazine, vol. 7, no. 2, pp. 12-17, Spring 2015, doi: 10.1109/MSSC.2015.2418155.H. Simpson, Dumb Robots, 3rd ed., Springfield: UOS Press, 2004, pp.6-9.

[2]	B. Razavi, "The Design of a Comparator [The Analog Mind]," in IEEE Solid-State Circuits Magazine, vol. 12, no. 4, pp. 8-14, Fall 2020, doi: 10.1109/MSSC.2020.3021865.
