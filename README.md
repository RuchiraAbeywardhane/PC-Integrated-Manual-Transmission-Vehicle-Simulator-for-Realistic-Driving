<h1 align="center" id="title">Manual Transmission Vehicle Simulator</h1>

<p align="center"><img src="https://github.com/RuchiraAbeywardhane/Manual-transmission-Vehicle-Simulator/blob/6b34faca125f20301f06f9bede190b22e4168e91/Images/MainImage1.jpg" alt="project-image"></p>

<p id="description">This is a comprehensive manual gear vehicle simulator that can be seamlessly connected to any computer equipped with the necessary software. This simulator offers an immersive and realistic experience of driving a manual transmission vehicle enhancing user skills and understanding of manual gear shifting.</p>
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Manual Transmission
*   Clutch Control Compatibility
*   Analog controlled Steering Wheel
*   Analog Controlled Acceleration
*   Analog Controlled Acceleration
*   Analog Controlled Brakes and Clutch
*   PS3-compatible USB Connection  
<br>
<h2>💻 Built with</h2>

Technologies used in the project:

*   Arduino
*   Analog Electronics
*   Unojoy Arduino Library


<br>
<h2 align="left" id="title">Working Concept</h2>
<br>
<p align="center"><img src="https://github.com/RuchiraAbeywardhane/Manual-transmission-Vehicle-Simulator/blob/f9349dea7dd1fa0874288fdfa47b9133517e2884/Images/WorkingConcept.png" alt="concept-image"></p>

*  <h3> Analog Reading from Steering Wheel </h3> Variable Resistor is mapped to the physical motion of the steering wheel. In order to have realistic motion for the wheel 1:3 ratio of gear wheels are used in between the Steering Wheel and the variable resistor allowing the user to turn the steering wheel full circle for one direction

*  <h3> Analog Reading from Pedals</h3> Variable Resistor is mapped to the physical motion of three pedals.  In order to have realistic motion springs are used with different spring constants according to the pedal. 

*  <h3> Gear Box</h3> Sensitive push buttons are used to detect the current gear in the gearbox. Clutch control necessary for Gear shifting is handled through the simulation software installed in the computer.

*  <h3> Arduino</h3> Arduino Uno board is used as the connection between the computer and simulating hardware. Here Arduino board does not get recognized as a uno board by the computer but as a PS3-compatible USB game controller. In order to do this firmware in the Arduino board is updated using Arduino Unojoy library.

<br>
<h2>Exhibited at EXMO 2023 at University of Moratuwa</h2>
<p align="center"><img src="https://github.com/RuchiraAbeywardhane/Manual-transmission-Vehicle-Simulator/blob/0cebf42378af27886ae8a9f8b109426e76593bc1/Images/EXMO.png" alt="EXMO-image"></p>
