# Python-code-for-Ion-acceleration

Modeling Ion Thruster Exhaust Velocity Using Python

Kurt Croker – Undergrad Mechanical engineering
Donnie Webster – Undergrad Computer Science

This project develops a Python-based model to investigate the effect of accelerating voltage on ion thruster exhaust velocity. Using conservation of energy principles, the relationship between electric potential and kinetic energy is used to calculate the exhaust velocity of Xenon, Krypton, and Argon Ions. The model used allows users to select a propellant and accelerating voltage, then computes the resulting exhaust velocity. Results are compared among propellants to examine the influence of ion mass on thrust performance.

Assumptions
	All ions are singly ionized
	Ion charge is q=1.602e-19C
	Collisions between particles are neglected
	All potential electrical energy is converted into kinetic energy
	Vacuum conditions are assumed

Ion thrusters accelerate charged particles using electric fields to produce thrust for spacecraft propulsion, positively charged ions are repelled from a positively charged grid to a negatively charged accelerator grid generating thrust as they exit out of the exhaust at a high velocity.

The motion of an ion accelerated by an electric potential difference can be modeled using several physical equations and simulated using software such as Python. When an ion is accelerated through a voltage difference V, the electrical potential energy supplied by the field is converted into kinetic energy. This relationship is described by:
qV=1/2 mv^2

Where:
	V= electric potential difference (volts) 
	q= charge of the ion (coulombs) 
	m= mass of the ion (kg)  
	v= velocity of the ion (meters per second) 
Rearranging the equation to solve for velocity gives:
v=√(2qV/m)
This equation can be used to model the exhaust velocity of ions such as Xenon, Argon, and Krypton under varying acceleration voltages.
For this project we will be modeling using a singly ionized Xenon, Argon, and Krypton
Xenon (m=2.18e-25 kg)
Argon (m=6.62e-26 kg)
Krypton (m=1.39e-25 kg)

When ionized atoms typically lose an electron and become slightly positively charged. The lost electron has a mass of about 9.11e-31 kg, which is negligible compared to the mass of the atoms themselves, so for calculations we will treat the mass of the ion as equal to the mass of the atom.

The user is prompted to select what kind of propellant they will be using within the interface, and are then asked to input the electrical difference between the positive and negative grids

