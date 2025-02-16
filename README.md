# EXPERIMENT-1
#### DC, AC and transient analysis of common source amplifier using LTspice

### AIM: 

To simulate the DC, AC and transient anlysis of common source amplifier using LTspice.

### COMPONENTS REQUIRED:

LTspice simulation software and 180um library files

### CIRCUIT DIAGRAM

![LT SC](https://github.com/user-attachments/assets/b7fcf9cd-cf47-4cff-a80a-93426c82dcda)

### PROCEDURE:
#### 1. DC Analysis
* Design the circuit as per the given circuit diagram.
* Right click on power supply and set as input voltage 0.9v and VDD as 1.8v.
* Go to simulate and select the configure analysis.
* Select the DC op pnt and run the simulation.
  ![image](https://github.com/user-attachments/assets/4c472f89-bbfc-4ee4-ae45-14294029eebb)


#### 2. AC Analysis
* Set the input as sine function and set dc offcet as 0.9v, amplitude as 50mv, frequency as 1khz and ac amplitude as 1.
* Go to simulate and select the configure analysis.
* select the AC analysis and set time to sweep as decade, start frequency as 0.1hz and stop frequency as 1Thz
* Click on run simulation and select the input point and output point.

#### 3. Transient Analysis
* Set the input values as per ac anlysis values.
* Go to simulate and select the configure analysis.
* Select the transient and set stop time as 1ms.
* Click on run simulation and select the input point and output point.
