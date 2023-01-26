# -Motor-speed-control
 This repository consists of the following units:

1. This is C code for a program that controls the speed of a motor using a PID controller on a PIC microcontroller. The program uses the LCD and UART modules to display the current speed of the motor and the PWM module to control the duty cycle of the motor. The program uses the external interrupt and timer modules to measure the speed of the motor, and the program uses the variables kp, ki, and kd to tune the PID controller. The program sets the initial speed of the motor to 100 RPM, and the user can change this by sending a value through the UART module. The program uses the PWM1 and PWM2 modules to control the direction of the motor. The program uses the Timer1 module to measure the speed of the motor, and the external interrupt module to count the number of pulses.
2. Simulations done in PROTEUS
The user of this repository must take care of the pid controller settings within 1.

Also, the code must be changed depending on the type of  encoder.

![proeject](https://user-images.githubusercontent.com/100707842/207294738-998cf032-65bd-41b7-bcb4-0f0531e99687.jpg)



![Screenshot_4](https://user-images.githubusercontent.com/100707842/207296521-e5ee6d16-a4a0-4737-bc9b-dc1a17286af7.jpg)

