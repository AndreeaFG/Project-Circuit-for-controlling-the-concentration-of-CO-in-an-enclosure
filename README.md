# Project-Circuit-for-controlling-the-concentration-of-CO-in-an-enclosure

This project involved designing a system that monitors and controls the concentration of carbon
monoxide (CO) in an enclosed space using a resistive gas sensor. The sensor detects CO levels in the
range of 300–10000 ppm, triggering a fan to introduce fresh air when the upper limit is reached and
stopping it when the lower limit is met. The sensor's resistance variation (90kΩ to 45kΩ for 100–
12000 ppm) was converted into a voltage range of 2V to 16V (given Vcc = 18V). The electrical
diagram includes the current source stage, the output voltage conversion stage, the hysteresis
comparator, and the relay, which controls the fan. The fan status (on/off) is signaled by a red LED. I
verified the projection and demonstrated correct operation through simulations performed with the
OrCAD X Professional Plus package. The Capture CIS modules are used for entering the schematic
and PSpice for running the simulations.
