# Arduino-Based-Robots
Arduino Based Robots | Line Follower Robot,Obstacle Controlled Robot and Bluetooth Controlled Robot by referring projects from roboindia

# Line Follower Robot
1) Working of a line follower robot is based on the IR
transmitters and receivers which are also called photo diodes .
2) When infrared rays transmitted by IR transmitter, fall on a
white surface, rays are reflected back and received by IR
receiver which generates some voltage changes.
3) When infrared rays transmitted by IR transmitter, fall on a
black surface, rays are absorb by the black surface and no rays
are reflected back, thus IR receiver does not receive any light
and no voltage changes occur.
4) When IR sensor senses white surface, then Arduino gets 1
as input and when sensor senses black surface, Arduino gets 0
as input.
5) IR sensor can be calibrated according to need of the user.


# Obstacle Avoiding Robot
1) Ultrasonic sensors measure the front distance, right
distance and left distance.
2) Servo motor is firstly aligned at 90 and then it moves
according to the code.
3) A maximum distance is defined and robot moves forward,
backward, left and right according to code,to
avoid obstacle



# Bluetooth Controlled Robot
1) It consists of a transmitter and a receiver section. The
transmitter end consists of Smart-phone Bluetooth and the
Android app installed on it. Similarly, the Receiver section
has Arduino board as a processor, HC-05 Bluetooth Module
as a wireless communication module, L293D for driving
motors.
2) Command which we give in app ,are processed by phone.
Command is then sent to the receiver side via Bluetooth.
3) Command received via Bluetooth is forwarded to Arduino
Uno board using UART serial communication protocol.
Arduino code checks the commands received.
4) Whenever the command is a matching string, Arduino
controls the movements of the robot accordingly in forward,
backward, right and left direction .


