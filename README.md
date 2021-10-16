# Arduino cardiograpf(ECG Arduino).
Building a cardiograph with Arduino and Processing.

An ECG sensor with electrodes is attached directly to the body to detect the heart rate. 
The ECG sensor electrodes convert the heartbeats into an electrical signal.
 ECG sensors are very light, thin, and accurately measure and provide data on continuous heart rate. 
The electrodes of the ECG sensor have 3 contacts and are connected by a cable approximately 70-80 centimeters long. 
This makes the sensor easy to connect to the controller and fits easily into a pocket. 
In addition, the plug-in cable is an audio plug, which makes this cable easy to remove or plug into the amplifier board. 
The sensor is designed to measure the pulse on the arm and the pulse on the leg.
To create a cardiograph, we need:
1. ECG Module with AD8232 IC and ECG sensors.
The AD8232 module provides access to the nine pins of the AD8232. SDN, LO +, LO-, OUTPUT, 3.3V, GND pins provide the necessary lines to operate the IC with an Arduino or other development board. 
This board also provides RA (right arm), LA (left arm), and RL (right leg) lines for attaching and using your own sensors.
In addition, there is an LED indicator that will display the pulse rate.
 The module operates at 3.3V. 
The biomedical touch pad can be connected to the 3.5mm jack or use the 3-pin jack.
2. Arduino nano module (version 3).
You can use other versions of Arduino, but you may need to change the sketch and wiring diagram.
3. Prototyping board. 
It is needed for ease of assembly and ease of debugging of the cardiograph.
4. Wires. 
Needed to connect components.
5. To reduce the resistance of the skin of the body and improve the quality of the recorded signal, you may need an ECG gel or saline solution.
The connection diagram is in a separate file called "schematic".
For assembly, you need to download sketches and connect the modules according to the scheme.

