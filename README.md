# robot2017

Tank style controls.  Arm that raises and lowers.  Hand that rotates, and opens and closes and a catapult

## Controller / Remote
Joystick mapping:
* Ch3(Left Joystick up/down) - Left Wheel
* Ch2(Right Joystick up/down) - Right Wheel

Buttons mapping:
* Btn7L - Changes the Mode
* Btn7U - Catapult Launch
* Btn7D - Catapult Reset
* Btn8L - Rotate Hand Left
* Btn8R - Rotate Hand Right

* Mode0:
  * Btn5U - Raise Arm
  * Btn5D - Lower Arm
  * Btn6U - Open Hand
  * Btn6D - Close Hand
* Mode1:
  * Btn5D - Open Hand
  * Btn6D - Close Hand
  * Btn7U - Raise Arm
  * Btn7D - Lower Arm

## Brain
Motor Mapping:
* port3 - Left Wheel
* port4 - Right Wheel
* port8 - Hand Rotate
* port7 - Arm Up and down

Servo Mapping:
* port2 - Catapult
* port5 - Left side of hand
* port6 - Right side of hand