# Requirements

## Introduction
 The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In European countries, the temperature is very low and any electronic designer should make sure that his equipment should work efficiently in that whether. 
In our project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature. In our project we have used ATmega328 microcontroller along with temperature sensor, Switches, Heat generator,and LCD diplay,etc.

## Features
- The System will sense is driver or passenger seated or not.
- Driver or Passenger has the access to modify the temperature in the vehicle.
- As per Drivers request, Heater will generate the heat accordingly.
- It is best for European Countries.
- Low cost and robust system.
- Modular Approach.

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the vehicles.
- Modular Approach
- Low cost and Robust system.

### Weakness
- Its only applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

## 4W's and 1'H
### **WHAT** : Vehicle seat heating system
### **WHERE** : Used in Automotives
### **WHEN** : At low Temperatures

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1    | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE | 






Circuit diagaram


TEST CASES

Case1: When both the Seat Switch and HeaterSwitch turned off
Case2: When Seat Switch is on and Heater Switch is OFF
Case 3: When Seat switch is OFF and Heater Switch is ON
Case4: When both the switches are ON


