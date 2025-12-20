---
layout: project
title: ENGRD 2210 Analysis
description: Thermodynamic Analysis
technologies: [N/A]
image: /assets/images/engrd-2210-analysis/photo.png
---

For ENGRD 2210, I was assigned to select a real-world device and to analyze it in a thermodynamic context. I selected the Speedway Chevy SBC/BBC Universal Aluminum Radiator.

---

#### Schematics
![Schematics]({{ "/assets/images/engrd-2210-analysis/schematics.png" | relative_url }}){:. style="width: 600px"}

---

#### Description
The radiator works as a heat exchanger between the coolant that circulates through the engine and the air. A pump is used to circulate the coolant while a fan forces air through the radiator. The hot coolant transfers heat to the cold air, and this heat transfer across a finite temperature difference generates entropy. 

---

#### System Diagram
![System Diagram]({{ "/assets/images/engrd-2210-analysis/system-diagram.png" | relative_url }}){:. style="width: 600px"}

---

#### Assumptions
- Steady-state
- The system does not do work
- There is no heat transfer between the system and surroundings
- Negligible kinetic and potential energy changes
- Mass flow rate = 2.5 kg/s for coolant
- Constant specific heat = 4.18 kJ/kg K for coolant
- Inlet temperature = 365 K for coolant
- Outlet temperature = 350 K for coolant
- Mass flow rate = 1.5 kg/s for air
- Constant specific heat = 1.01 kJ/kg K for air
- Inlet temperature = 300 K for air
- Outlet temperature = 403 K for air

---

#### Mass Balance
![Mass Balance]({{ "/assets/images/engrd-2210-analysis/mass.png" | relative_url }}){:. style="width: 600px"}

---

#### Energy Balance
![Energy Balance]({{ "/assets/images/engrd-2210-analysis/energy.png" | relative_url }}){:. style="width: 600px"}

---

#### Entropy Balance
![Entropy Balance]({{ "/assets/images/engrd-2210-analysis/entropy.png" | relative_url }}){:. style="width: 600px"}

---

#### Performance
A change to the radiator that would improve the device performance would be increasing the mass flow rate of the air while maintaining its inlet and outlet temperatures as well as the inlet temperature and the mass flow rate of the coolant. Increasing the mass flow rate while maintaining the inlet and outlet temperatures of the air would increase the amount of heat transferred between the coolant and the air, and maintaining the inlet temperature and the mass flow rate of the coolant would require a decrease in its the outlet temperature in order to account for this increased heat transfer. Therefore, increasing the mass flowrate of the air while maintaining its inlet and outlet temperatures as well as the inlet temperature and the mass flow rate of the coolant would improve the performance of the radiator.

---