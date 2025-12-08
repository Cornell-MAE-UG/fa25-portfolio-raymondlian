---
layout: project
title: Thermo
description: 
technologies:
image: /assets/images/Nozzle.png
---


Raymond Lian  
Thermodynamic device: nozzle of a gas pump  
Schematic of a nozzle						picture of a nozzle
![][image6]									![][image7]
Description of Nozzle  
A nozzle is a type of thermodynamic device that increases the speed of the fluid as it passes. In this example, the fluid is gas and the nozzle increases the speed of the gas as it exits the nozzle which is useful to move the gas into the gas tank of a car. This speeding up process is due to the change in cross sectional area of the nozzle. The gas goes through a large cross sectional area in the tube then when it reaches the nozzle, the cross sectional area gets smaller. This decrease in cross section area is responsible for increasing the speed of the fluid.   
System Diagram  
This is a control volume system because we are only tracking the fluid inside the nozzle. We have gas entering the nozzle from the larger cross section area and exiting from the smaller cross section area. The nozzle is adiabatic so no heat transfer and it doesn’t produce or require work.  
For the following equations, we are assuming steady state and adiabatic.  
Mass Balance:  
![][image1]

Energy Balance:  
![][image2]  
E dot \= 0 because steady state  
Q dot \= 0 because adiabatic nozzle  
W dot \= 0 because nozzle does no work  
Neglect delta PE because it’s very small  
Resulting equation:  
![][image3]  
Entropy Balance  
![][image4]  
	S dot \= 0 because steady state  
	Q dot \= 0 because adiabatic nozzle  
	Resulting equation:  
![][image5]  
Change and effect  
Many different changes can be made depending on the goal of the nozzle. For a nozzle in a gas pump, we don’t need the speed of the gas exiting the nozzle to be too high or else it will cause turbulence inside the gas tank when high speed gas hits the gas tank. However if we want to water the grass that is 20 feet away, then we want a nozzle of a garden hose that can increase the speed enough so that the water can travel that far distance. One way of achieving this range is to decrease the exit cross section area. If the exit cross section area is decreased, then the the velocity of the exit water has to increase in order to balance the mass equation 

If Aout decreases, Vout has to increase to maintain balance. For the nozzle in a gas pump, we want Aout to be a little bit smaller than Ain because we still want to speed up the gas but we don’t want the gas to exit with too great of a speed.  
Example with real numbers  
Liquid water enters a steady, adiabatic nozzle at p1 \= 600 kPa, T1 \= 25 ℃, **V1** \= 5 m/s and exits at p2 \= 200 kPa, **V2** \= 55 m/s. Ain \= 3 cm2. Assume steady isentropic and adiabatic operations;  neglect height change. Find mass flow rate, exit temperature T2, Entropy generation Sgen dot.  
Solution:   
m dot \= ρAinVin  \= 997kg/m3 \* (0.0003 m2) \* (5 m/s) \= 1.50 kg/s

	Sgen dot \= 0 because of isentropic assumption

image1: /assets/images/Mass Balance 2.png

image2: /assets/images/Energy Balance.jpeg

image3: /assets/images/Energy Balance SS.jpeg

image4: /assets/images/Entropy Balance.jpeg

image5: /assets/images/Entropy Balance SS.jpeg

image6: /assets/images/Schematic.jpeg

image 7: /assets/images/Nozzle.png