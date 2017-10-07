# robot2017

```
#pragma config(Motor,  port2,           catapult,  tmotorServoStandard, openLoop)
#pragma config(Motor,  port3,           leftMotor,     tmotorVex393_MC29, openLoop, reversed)
#pragma config(Motor,  port4,           rightMotor,    tmotorVex393_MC29, openLoop)
#pragma config(Motor,  port5,           handLeft,      tmotorServoStandard, openLoop, driveRight)
#pragma config(Motor,  port6,           handRight,     tmotorServoStandard, openLoop, driveLeft)
#pragma config(Motor,  port7,           armMotor,      tmotorServoStandard, openLoop)
#pragma config(Motor,  port8,           handMotor,     tmotorServoStandard, openLoop)

/********************************

Joystick mapping:
	Ch3(Left Joystick up/down) - Left Wheel
	Ch2(Right Joystick up/down) - Right Wheel
Button mapping:
	Btn7L - Changes the Mode
	Btn7U - Catapult Launch
	Btn7D - Catapult Reset
	Btn8L - Rotate Hand Left
	Btn8R - Rotate Hand Right

	Mode0:
		Btn5U - Raise Arm
		Btn5D - Lower Arm
		Btn6U - Open Hand
		Btn6D - Close Hand
	Mode1:
		Btn5D - Open Hand
		Btn6D - Close Hand
		Btn7U - Raise Arm
		Btn7D - Lower Arm

********************************/
```