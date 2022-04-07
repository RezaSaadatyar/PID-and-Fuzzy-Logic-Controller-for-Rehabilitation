***PID and Fuzzy Logic Controller for Rehabilitation***

Comparison of performance between a PID-tuned controller and a fuzzy controller for the development of rehabilitation exoskeletons
The simulation of the developed controller has been carried out using Matlab/Simulink

![Fig 1](https://user-images.githubusercontent.com/96347878/162259389-4400e43f-bd2a-4799-a121-76d91cd96dff.png)

***PID and Fuzzy Logic simulation configuration:***
* PID Ziegler Nichols Controller (PID-ZN): 
Matlab SISO design tool is used to simulate and implement PID controllers. For good step response, tuning process is necessary. The value of Kp, Kd, and Ki are varied incrementally in Simulink block until the response shows no overshoot.

![Fig 2](https://user-images.githubusercontent.com/96347878/162265100-7f7967b2-1d5c-4655-a6cb-6af059be2bb0.PNG)

![Fig 3](https://user-images.githubusercontent.com/96347878/162269387-a472d9a4-4364-47ea-8245-ba9504440c86.PNG)

![Fig 2](https://user-images.githubusercontent.com/96347878/162275035-f5b5e006-77b4-416b-b155-d3705f260395.PNG)

* PID Cohen Coon Controller (PID-CC): Three process characteristics are used in Cohen-Coon tuning: process gain, dead time, and time constant. Step tests are used to determine these characteristics.

![Fig 4](https://user-images.githubusercontent.com/96347878/162278645-126dbe31-1743-4534-b173-b125779ebe1a.PNG)

![Fig 3](https://user-images.githubusercontent.com/96347878/162278746-d57c304c-72ff-4e30-8831-edff4271b1da.PNG)
