***PID and Fuzzy Logic Controller for Rehabilitation***

Comparison of performance between a PID-tuned controller and a fuzzy controller for the development of rehabilitation exoskeletons
The simulation of the developed controller has been carried out using Matlab/Simulink

![Fig 1](https://user-images.githubusercontent.com/96347878/162259389-4400e43f-bd2a-4799-a121-76d91cd96dff.png)

***PID and Fuzzy Logic simulation configuration:***
* PID Ziegler Nichols Controller (PID-ZN)
Matlab SISO design tool is used to simulate and implement PID controllers. For good step response, tuning process is necessary. The value of Kp, Kd, and Ki are varied incrementally in Simulink block until the response shows no overshoot.
