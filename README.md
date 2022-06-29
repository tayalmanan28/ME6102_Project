# ME6102 Project
Force Controlled Compliant Gripper

1. 3D printed a three finger compliant PLA arm capable of conforming to the object’s geometry for gripping
2. Used a servo motor to actuate the gripper with a feedback system and pressure sensors for controlling force
3. Simulated the dynamics of the gripper in MATLAB using the SynGrasp toolbox by superposing torsional spring behaviour at the hinges of finger joints for approximating the compliant behavior of the gripper
## Wiring Diagram
<img src="media/arduino-force-sensor-wiring-diagram.jpg" alt="gripper" height="200"/>

## Things Needed and Cost (in INR)
| THINGS NEEDED         | SPECS                                                                                                                 | Quantity | Cost(Rs) |
| --------------------- | --------------------------------------------------------------------------------------------------------------------- | -------- | -------- |
| Servo motor           | TowerPro MG 995 Metal Gear Servo Motor (180 deg rotation)<br>                                                         | 1        | 450      |
| 3D Printed Model      | Flexible PLA                                                                                                          | 0.3kg    | 360      |
| Piezo-electric Sensor | Lead zirconate titanate-piezoelectric ceramic material | 3        | 55       |
| Microcontroller       | Arduino UNO                                                                                                           | 1        | 500      |
| Rubber Grip           | Lead zirconate titanate-piezoelectric ceramic material                                                                | 3        | 150      |

## Images of Compliant Gripper
<p float="left">
  <img src="media/gripper.jpg" alt="gripper" height="200"/>
  <img src="media/gripper_1.jpg" alt="gripper" height="200"/>
</p>

## Gif
<p float="left">
  <img src="media/Compliant_Gripper.gif" alt="gripper" height="200"/>
  <img src="media/Force_Sensor.gif" alt="gripper" height="200"/>
</p>
