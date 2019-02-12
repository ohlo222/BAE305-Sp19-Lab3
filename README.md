# BAE305-Sp19-Lab3
# By: Spencer Givan, Chrissy Witt, Olivia Lohre
# Summary
The first part of this lab is how Circuit simulation is formed online. This is a helpful tool for when there is trouble measuring accurate values, or before you build the physical circuit you can have an estimation of what values your circuit should be reading. Computer software circuit simulators can also calculate ideal theoretical behavior from Kirchhoff’s Laws and allows you to try out many variations of the designed circuit. So, in this lab we will be using using the simulation software provided to verify Kirchhoff’s voltage law (KVL) and Kirchhoff’s current law (KCL), and to apply Thevenin’s and superposition theorems to the analysis of electrical circuits.

Our Overall Tasks are
- To verify the validity of KVL and KCL laws.
- To apply the superposition and Thevenin’s theorems to the analysis of electrical circuits.
- To confirm the validity of Thevenin’s and superposition theorems.

# Materials
- DC Power Supply
- Breadboard 
- Resistors with the following values, (in Ohms, K = 10^3)
  - 220, 1K, 2.2K, 3.3K, 4.7K, 6.8K, 10K, 470K
- Generic Digital Multimeter (DMM)
- Laptop to access Partsim.com and TinkerCAD.
  
# Assembly Procedures
Build the circuit below for Part 1.
----Insert the circuit in series-----
Build the circuit below for Part 2.
----Insert the circuit in parallel-----

# Test Equipment

# Test Procedures
Part 1. Series Circuit
-	Using voltage probes from the provided DMM, measure the voltage drop across each resistor in the above circuit (both simulation and on the breadboard).
- Using the current probe measure the current in the circuit (simulation only – We have lost too many multimeter fuses!).
- Record the results.

Part 2. Parallel Circuit
- Measure and record the branch currents I1, I2, I4, I5, I6, I7. (Branch numbers refer to resistors.) Make sure to identify the direction of the current as this will have an impact on the circuit.
- Verify that the current leaving is equal to the current entering any node.

Part 2.2 KVL
- Using voltage probes from the provided DMM, measure and record the voltage drop across all resistors. R1-R8. From the second circuit.

Part 3. Potentiometer
- Given a sensor that ranges from 0-19.650K Ohms and a 14.1V input voltage, determine the correct resistance (R?) to place in series with the sensor to yield a voltage output between 0-5V across the sensor. Below is the provided visual aid for the problem.
------Insert Circuit Picture------

Part 4- TinkerCAD Circuits
- Login to TinkerCAD Circuits. (An online website)
- Start a simulation and in the components drop down switch to "Starters->Arduino" and select "Blink".
- Find and run the starter Analog Input. This should change the rate of blinking of the light on the arduino.


# Test Results
------Insert Table of Results-----
------Insert TinkerCAD------
# Discussion
From an overall standpoint, the values that were simulated on PartSim were very close to the actual measured values. This showed that the errors could be caused by human error and that the circuits were properly built.

- Q1: In your lab report show currents entering and leaving a node using equations. (Ex: I5 = I6 + I7). 

- Node 1 
  - I1 = I2 + I4 + I5

Simulated: 2.633mA = 0.944mA + 0.662mA + 1.026mA
Actual: 

- Node 2
  - I5 = I6 + I7
  
 Simulated: 1.026mA = 1.015mA + 0.009299mA
 Actual: 

- Q2: Which branches have the same voltage? Which do not?

When looking at the voltage across branches R2 and R3 is the same voltage as R4. As well as, R6 is equal to R7 and R8. Meaning, they share the same nodes and are in parallel with each other. So, wehn they are placed in series, it creates a voltage difference across the resistor. Because R5 is in series with the two branches in parallel, this creates the two different voltages. 


- Q4: What is the sensor resistance (R1) when the sensor reads 3.63V?

- Q5: What is the sensor resistance (R2) when the sensor reads .354V?

- Q6: What is the sensor resistance (R3) when the sensor reads 1.09V?

- Q7: If the maximum current for the sensor is .4mA, will the sensor work with this circuit? What is the maximum current for this circuit?
