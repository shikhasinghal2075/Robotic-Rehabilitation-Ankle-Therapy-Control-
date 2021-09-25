# Robotic Rehabilitation for Ankle Therapy Control

Rehabilitation robotics is a field of research dedicated to understanding and augmenting rehabilitation through the application of robotic devices.
Rehabilitation robotics includes development of robotic devices tailored for assisting different sensorimotor functions(e.g. arm, hand, leg, ankle),
development of different schemes of assisting therapeutic training, and assessment of sensorimotor performance of patient; here, robots are used mainly
as therapy aids instead of assistive devices.
The Robo Rehab application made using MIT app inventor controls the working of machine designed for robotic rehabilitation for ankle movement control.
The application interacts with Arduino Uno via Bluetooth module HC-05.

## WORKING
-The user enters the required fields such as Dorsi and Plantar angle, Therapy time and Hold time in each position.
-Then this data is fed to micro-controller (ARDUINO UNO) and it further reads current angle of machine and then according to input data it starts the
upward or downward movement of machine.
-The process continues till therapy time entered via app and then the machine stops.
-The application also provides an emergency STOP button, to cancel the process in between if required.
-Also therapy information and patient information can be saved using the application in the mobile. 
