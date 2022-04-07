***PID and Fuzzy Logic Controller for Rehabilitation***

Comparison of performance between a PID-tuned controller and a fuzzy controller for the development of rehabilitation exoskeletons
The simulation of the developed controller has been carried out using Matlab/Simulink

![Fig 1](https://user-images.githubusercontent.com/96347878/162259389-4400e43f-bd2a-4799-a121-76d91cd96dff.png)

***PID and Fuzzy Logic simulation configuration:***
* PID Ziegler Nichols Controller (PID-ZN): 
Matlab SISO design tool is used to simulate and implement PID controllers. For good step response, tuning process is necessary. The value of Kp, Kd, and Ki are varied incrementally in Simulink block until the response shows no overshoot.

![Fig 2](https://user-images.githubusercontent.com/96347878/162265100-7f7967b2-1d5c-4655-a6cb-6af059be2bb0.PNG)

![Fig 3](https://user-images.githubusercontent.com/96347878/162269387-a472d9a4-4364-47ea-8245-ba9504440c86.PNG)

![Fig 2](https://user-images.githubusercontent.com/96347878/162274751-733eebad-7d4b-4cda-8d8f-0990a5be2c65.PNG)

* PID Cohen Coon Controller (PID-CC): 
