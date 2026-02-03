---
title: Module's Requirements
---

## Module Requirements
The following sections document the requirements that the this module needs to fulfill for the Wireless communication subsystem of the ground search and rescue drone.

| **Requirement Description** | **Measure of<br> Threshold** | **Target<br>Measure** |**Stretch<br>Requirement<br>(Y-N)**|
|-----------------------------| ----------------- | ----------------- | :-----: |
| Surface mounted, 3.3V switching power regulatore | 3.2 Volts | 3.3 Volts | No |
| Surface mounted microcontroller | 1 PIC or ESP | 8-bit PIC | No |
| Wireless Communication | Able to send or receive a Wi-Fi data | Send and receive Wi-Fi Data to MQTT | No |
| Large working range | 30 Meters | 5 Kilometers | Yes |
| Live Video | 30 FPS | Less than 3 second delay | Yes |
| Remote control over Wi-Fi | Control within 10 Meters | Control within 30+ Meters | No |
| Human Design Interface | Small OLED screen with pushbuttons that permits a user to view all sensor data in text; directly control the actuator; modify setpoints on all the system boards; toggle GPIO debug pins on ALL subsystems | Ability to tune sensors and actuators with controls on exterior of device | No |
| I2C or SPI | Control peripheral devices such as sensors, microphones, and camera | Same as MOT | No |
| Daisy chain UART | Daisy chain UART connection between all subsystems | Separate UART loops for high speed communication through certain subsystems | No |
