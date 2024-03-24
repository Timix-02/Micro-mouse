# Micro-mouse
The micro-mouse project entails the design and implementation of a maze-solving robot, [Veritasium video](https://www.youtube.com/watch?v=ZMQbHMgK2rw). The design will concentrate on the hardware design, supplemented by minor software components, within a strict budgetary framework. Project components are subdivided into four modules: processor, motherboard, sensing, and power. While the motherboard and processor modules are pre-designed, the focus lies on developing the sensor and power modules.

The power module is tasked with the holistic power supply of the system, encompassing motor functionality and battery charging. Design considerations necessitate compatibility with motherboard pin headers and an appropriate form factor for integration with the robot.

Conversely, the sensor module is responsible for object detection/sensing. It must seamlessly integrate with motherboard pin headers and align with robot size specifications.

Successful project completion hinges upon a comprehensive understanding of the module's role within the overall system architecture, coupled with meticulous adherence to specified requirements. Group members assume responsibility for either the power or sensing subsystem. 

PCB manufacturing is done by JLPCB, thus components are limited to their inventory

##Sensing Subsytem
The sensor PCB functions as the "eyes" of the robot, providing crucial obstacle detection information to the processor. Key objectives for this submodule include:

1. Detecting obstacles in front of and possibly on the sides of the robot.
2. Implementing switching mechanisms to conserve power during idle periods.
3. Ensuring system reliability through rigorous testing and validation.
4. Managing power consumption to avoid premature battery depletion.
5. Developing code to interface the sensor with the processor, demonstrating effective wall detection.

The sensor board must align with the 2x14 connection standard and be appropriately sized for integration with the robot. Pin assignments for the sensor board's connection to the motherboard are provided, indicating the associated functions and their respective pin numbers.

Successful completion of the sensor subsystem necessitates a comprehensive understanding of its role within the overall system architecture, coupled with meticulous adherence to specified requirements. This includes ensuring seamless integration with other subsystems and addressing power management challenges to maintain overall system efficiency.





