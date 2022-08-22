With regards to PID control, one must take note of some general tuning rules.
Increasing the integral component helps to arrive at the set point much faster.
However, the proportional component must be a certain measure higher than the integral component for overall system stability.
For safety, one must start the kp and ki component at relatively low levels
They should be slowly increased proportionally with one another to reduce the settling time, Hence, making the control response faster.

The main control loop is in the tmr1.c file
Variable Initializations are present in the main.c file
The steps to realise PID control in the code are heavily commented
