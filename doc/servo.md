# class Servo - 3-wire pwm servo driver

Usage:
```python
from picar_4wd.servo import Servo

ser = Servo("P0")                     # create an Servo object from a pin
val = ser.set_angle(60)                   # set the servo angle
```
## Constructors
```class picar_4wd.servo.Servo(pin)```
Create an Servo object associated with the given pin which start with "P". This allows you to set the angle values.

## Methods
- set_angle(self, angle) - set the angle values between -90 and 90.
```python
set_angle(90)
```