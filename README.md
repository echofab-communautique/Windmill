# Windmill

## Description
The objective of the project is to make a windmill using recycled parts, such as an alternator from a Mazda 3 2000. 

####Alternator
An alternator is an electro-mechanical device that produces electrical energy from mechanical movement, it can be seen as the opposite of a motor. An alternator differs from a DC motor in that it contains no permanent magnets. Instead, there are two concentric wound coils of air within the alternator: a stator coil (the outside coil which does not rotate) and a rotor coil (the inside coil, attached to the alternator's puller, which does rotate). The rotor is also referred to as the alternator's "field".

An electromagnetic field is created when current flows through the field coil. The strength of the field is directly proportional to the amount of current flowing through the rotor. As the rotor moves clockwise, the resultant magnetic field sweeps clockwise through the outer coil of wire, and electricity is generated in the stator coil. Since the magnetic field sweeps back and forth through the stator coil, an alternating current is produced. The alternating current has a frequency equal to the frequency with which the alternator's pulley is rotating.
For this process to begin, the alternator's field must start with some kind of current. Rotating the rotor coil itself does absolutely nothing, unless there is current flowing through the coil, producing a magnetic field. Thus, it is necessary to have the alternator hooked up to a battery to supply this initial current.

Since the purpose of the alternator is specifically to charge batteries, the alternating current it produces is rectified through a diode bridge. The resulting current is direct current, which can be used to charge an attached battery. This DC current can also be used to supply the field coil with current during operation. As a result, the field coil draws current from the battery only until the alternator is capable of producing its own electricity. Once the alternator is producing electricity, it is self-sustaining. 

The voltage coming out of the alternator depends on two variables: the amount of current flowing through the field coil (i.e. the strength of the magnetic field) and the speed at which the alternator's field is rotating. The alternator has a regulator that tries to keep the voltage across the battery at a steady 14.4V (the optimal voltage to recharge 12V car batteries). It does this by regulating the amount of current flowing to the field coil. Once the alternator is self-sustaining, the only current flowing to the field originates from the alternator itself. If the output voltage is too low, the regulator increases the current flowing to the field coil. Simply put, as long as the alternator can maintain at least 14,4V across the battery, making the pulley spin faster or slower will have absolutely no effect on the power output. Power output in such case will depend only on the load attached to the alternator.

It is important to take note that before the alternator is self-sustaining, the current flowing to the field is unregulated. The initial current depends only on the resistance of the coil, the resistance of anything placed in series with the coil and the state of charge of the battery connected to the field coil.

When the car starts, it initially idles at 700 rpm. The pulley ratio between the crankshaft and the alternator is 3:1. Thus, the alternator rotates at a minimum of 2100 rpm. The current in the field coil -0.15 A- is enough to start the alternator at this particular rotational speed. If the alternator is operated at a lower rotational speed, however, a higher initial current is needed to produce enough electricity in the stator coil to start the alternator.

####Turbine

####Regulator
