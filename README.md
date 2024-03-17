# Electronic-Speed-Controller-ESC-
**Components Placement and Layout Considerations**
![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/64877777-5460-417e-87d6-ca7ab27c8843)
The ESC incorporates cutting-edge features, including a 3-phase inverter output filter, optimal DC link current sensing, and shaft encoder input, ensuring enhanced performance and efficiency in various industrial applications
**Intermediate and HF loop Capacitor**
![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/bc4ec546-df9d-4627-90e5-e4937bf07006)
Intermediate Capacitors: Intermediate capacitors refer to capacitors that are used in electronic circuits to store and discharge electrical energy in various applications. These capacitors typically have moderate capacitance values, falling between low and high capacitance ranges. They are commonly employed in power supply circuits, coupling and decoupling circuits, timing circuits, and signal filtering applications
### **Simulation Setup**
![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/f58e0856-e709-4f08-9e32-04d10913f834)


![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/71354811-3991-47fa-a336-1aa22f976b35)
upper graph depicts the current flowing across the Rshunt resistor, while the lower graph illustrates the corresponding output voltage of the sensor. As the output voltage of the sensor increases, we observe a proportional rise in the current across the Rshunt. This correlation between the two parameters indicates a direct relationship, where an increase in the output voltage of the sensor leads to a simultaneous increase in the current through the Rshunt resistor. This behavior is essential for accurate current measurement and control, as it allows precise monitoring of current levels based on the sensor's output voltage. Such a responsive and synchronized relationship ensures reliable and effective current sensing in various applications, providing valuable insights into the system's performance and facilitating optimal power management.
**Shaft Encoder Simulation**


![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/5bdc0422-71f9-4c75-8ad8-c5e0e75918f7)
This observation highlights the stability and reliability of the system's output signals. The constant voltage of 3.3Vdc across all phases is a crucial indicator of the accurate and precise operation of the electronic speed controller (ESC).
**BUCK CONVERTER**


![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/4fe52e67-ade3-4274-8726-c406b452e9dc)

**OCP fault** 

![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/97796624-60bb-457b-a682-93aab5f7979e)
The simulation circuit showcases a crucial function in the form of Over Current Protection (OCP). Designed to ensure the safety and integrity of the electronic system, the OCP circuit monitors the current flowing through the system and activates a protective mechanism in case of excessive current levels. 
**### FINAL PCB LAYOUT**


![Image](https://github.com/users/NaorBalas/projects/1/assets/162509440/bec4d075-3488-47fa-8e8a-16aa2ad02db6)
