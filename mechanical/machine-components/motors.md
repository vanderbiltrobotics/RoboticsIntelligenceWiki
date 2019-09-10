![D Profile Shaft](/uploads/machine-components/d-profile-shaft.jpg "D Profile Shaft")<!-- TITLE: Motors -->
<!-- SUBTITLE: Motor Selection -->

# Overview
Motors turn your electrical energy to kinetic energy. Simple. To pick what kind of motor (and gearbox) you need for the application, you need to consider the torque, speed, and weight/size constraints. You will probably want a conventional DC motor unless you have a special reason not to.

## Conventional DC Motor Specifications
While you can surely find motors from other locations/vendors, we will typically use https://www.vexrobotics.com for simplicity and reliability, along with a compatible gearbox . They have CAD models and specs such as free speed, current, and stall torque. The CAD model allows you to place them within the assembly to check for size constraints, free speed and stall torque allow you to decide the gearbox ratio (which there are also CAD models for), and current draw to estimate power consumption. The useful page to look at is https://motors.vex.com/, where you can find graphs comparing the torque, speed, current, and efficiency of the motors. Estimate the torque required for your mechanism, and apply a gear ratio such that the torque required for the motor lands on the high part of the efficiency curve. If the speed is too low/high, then a different motor might be considered. Also keep in mind the duty cycle (how long/often the motor is in operation during the run).
## Servos
Servo motors are smaller motors that are position controlled instead of speed. This means that they are much more precise, at the cost of torque and range of motion. It is very rare for a servo that we would be able to get to move more than a small camera or sensor. 
## Linear Actuators
Linear actuators is a motor that creates linear motrion, useful for extending in a straight line. Specs to look for are the fully extended length, the fully contracted length, and the maximum load it can support.