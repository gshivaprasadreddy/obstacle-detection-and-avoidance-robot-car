# obstacle-detection-and-avoidance-robot-car
Road accident is a major issue in many countries, mostly fast-moving vehicles face collision on roads. 
Another issue is the uncontrollable condition that if a person gets sleepy during the driving it can also cause 
collisions with nearby objects. Obstacle detection and avoidance can be considered as the central issue in 
designing mobile robots.
In this project we purpose the obstacle avoiding car which can automatically sense the obstacle in its way 
and avoid it by changing the direction. It is a robot vehicle that works on Arduino microcontroller and 
employs ultrasonic sensors to detect obstacles. On basis of sensor detection, the dc motor turns the wheel left 
or right and then moves forward according to the program which executing through Arduino software.
From its initiation in the 1950s, modern robots have come a long way and rooted itself as an immutable aid 
in the advancement of humankind. In the course of time, robots took many forms, based on its application, 
and its size varied from a giant 51 feet to microscopic level. During technological developments of robots, 
one aspect remained instrumental to their function, and that is mobility. The term “Obstacle Avoidance” is 
now used in modern robotics to denote the capability of robot to navigate over an unknown environment 
without having any collision with surrounding objects. 
Obstacle avoidance in robots can bring more flexibility in maneuvering in varying environments and 
would be much more efficient as continuous human monitoring is not required. This project developed an 
obstacle avoiding robot which can move without any collision by sensing obstacles on its course with the 
help of ultrasonic distance sensors. It will move in a particular direction and avoid the obstacles coming in 
between the path of robot. These robots guided with this technology can be put into diversified uses, e.g., 
surveying landscapes, driverless vehicles, autonomous cleaning, automated lawn mower and supervising 
robot in industries.
we proposed the solution
The obstacle avoidance robotic vehicle uses ultrasonic sensors for its movements. Arduino is used to 
achieve desired operation. The motors are connected through motor driver IC to Arduino. The ultrasonic 
sensor is attached in front of the robot. Whenever the robot is going on the desired path the ultrasonic sensor 
transmits the ultrasonic waves continuously from its sensor head. Whenever an obstacle comes ahead of it 
the ultrasonic waves are reflected from an object and that information is passed to the Arduino. 
The Arduino controls the motors left, right, back, front, based on ultrasonic signals. To control the speed 
of each motor pulse width modulation is used (PWM). When ultrasonic sensor detects the object which is 
kept inside the path it will send the signal toward the Arduino uno and according to that it will rotate the 
motor M3 & M4 in forward direction and rotate the motor M1 & M2 in reverse direction such way that the 
car gets moving in left direction. Similarly in every time whenever an obstacle in found to be in path of car it 
will detect it and rotate the car in left direction to avoid the obstacle
