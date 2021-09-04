Components Required - 
1. Arduino Uno x1
2. Arduino Nano x1
3. HC-05 Bluetooth Module x2
4. MPU-6050 x1
5. DC Motor 12V x4
6. L293D Motor Driver x1
7. 9V Battery (As per Requirement)

Tools Required - 
1. Soldering Iron
2. Solder
3. Tape
4. Screwdriver
5. Arduino IDE

This is about how to make a gesture-controlled car by yourself. Basically this is a simple application of MPU-6050 3-axis Gyroscope, Accelerometer. You can do many more things. by understanding how to use it, how to interface it with Arduino and how to transfer its data over the Bluetooth modules. in this writeup, I will be focusing on Bluetooth to Bluetooth communication, in between two HC-05 Bluetooth modules. 
Basically, HC-05 Bluetooth module comes with a slave module factory setting. that means we can send data to module jus by plug it in. no need to do any other setting to send data from mobile devices to the HC-05 module. just enter its default password (1234/0000)to connect it with.
We will send data through the Bluetooth module which will be used by the MPU-6050 gyro sensor to the another Bluetooth module.
