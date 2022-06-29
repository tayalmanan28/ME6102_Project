# ME6102 Project
Force Controlled Compliant Gripper

1. 3D printed a three finger compliant PLA arm capable of conforming to the object’s geometry for gripping
2. Used a servo motor to actuate the gripper with a feedback system and pressure sensors for controlling force
3. Simulated the dynamics of the gripper in MATLAB using the SynGrasp toolbox by superposing torsional spring behaviour at the hinges of finger joints for approximating the compliant behavior of the gripper
## Wiring Diagram
<img src="media/arduino-force-sensor-wiring-diagram.jpg" alt="gripper" height="200"/>

## Things Needed and Cost (in INR)
| THINGS NEEDED    | SPECS                    | Quantity          | Cost(Rs)      |
| ---------------- | ------------------------ | ----------------- | ------------- |
| Stepper Motor    | 87mm (3.4 inches) NEMA34 | 2                 |               |
| Springs          | Not Decided Yet

<br>    | 4                 |               |
| 3D Printed Model |                          | 1(Assuming 0.3kg) | 0.3\*1200=360 |
| pressure Sensor  |                          | 4                 | 160\*4=640    |
| Distance sensor  | HC SR 05                 | 2                 | 200\*2=400    |
| Rubber Grip      |                          | 2                 | 100\*2=200    |

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
