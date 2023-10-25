# -Auto-Tracking-Mounting-Plate-using-Arduino-M.
Here is the Project youtube link: 
https://www.youtube.com/watch?v=kUTNO0VBBsw

A servo motor, an ultrasonic sensor, and two infrared sensors have been used.
"Auto-Tracking Mounting Plate using Arduino," combines various hardware components with an Arduino microcontroller to create a system that can automatically track or follow a specific target or object. This type of system is often used in applications such as solar panel tracking, security camera tracking, or even art installations.
Here's a breakdown of the key components and their roles in this project:
1. **Arduino Microcontroller:** The Arduino acts as the brain of the system, responsible for processing data from various sensors and controlling the servo motor to adjust the position of the mounting plate.
2. **Servo Motor:** The servo motor is responsible for moving the mounting plate or platform. It can rotate to precise angles and is used to aim the mounting plate in the direction of the target or object to be tracked.
3. **Ultrasonic Sensor:** An ultrasonic sensor is often used to measure the distance between the mounting plate and the target. It emits ultrasonic waves and measures the time it takes for the waves to bounce back after hitting the target. This information can be used to calculate the distance.
4. **Infrared Sensors:** Two infrared sensors are likely used for detecting the presence of the target or object. Infrared sensors can be used to detect the heat emitted by objects or to identify if an object is present within a certain range.
The general operation of this system typically involves the following steps:
1. **Initialization:** The system starts by initializing all the components, including the servo motor, ultrasonic sensor, and infrared sensors.
2. **Target Detection:** The infrared sensors are used to detect the presence of the target or object. If the target is not within the range of the sensors, the system may go into a standby mode.
3. **Distance Measurement:** The ultrasonic sensor is activated to measure the distance between the mounting plate and the target. This data is essential for the tracking mechanism.
4. **Servo Control:** The Arduino uses the distance data to calculate the angle at which the mounting plate needs to be adjusted to face the target. It then commands the servo motor to move the plate accordingly.
5. **Feedback Loop:** This process is repeated continuously in a feedback loop, allowing the system to track the target as it moves. The Arduino adjusts the servo motor position as needed to keep the target in the center of the mounting plate.
This project can be extended and modified for various applications.
The success of the project depends on the accuracy and speed of the sensors, as well as the precision and responsiveness of the servo motor. The Arduino acts as the control unit that ties all these components together and ensures efficient tracking.
