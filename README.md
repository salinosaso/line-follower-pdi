# line-follower-pdi
Sample code on c++ for a simple yet powerfull line follower
I designed this for a sample robot used in MicroEW, the Kd, Ki and Kp needs to be found in order to work properly
you can use brute force to get them but I would recomend this: 
  -The proportional term produces an output value that is proportional to the current error value. The proportional response can be adjusted by multiplying the error by a constant Kp, called the proportional gain constant.
  -The integral term accelerates the movement of the process towards setpoint and eliminates the residual steady-state error that occurs with a pure proportional controller. However, since the integral term responds to accumulated errors from the past, it can cause the present value to overshoot the setpoint value (see the section on loop tuning).
  -Derivative action predicts system behavior and thus improves settling time and stability of the system.[16][17] An ideal derivative is not causal, so that implementations of PID controllers include an additional low-pass filtering for the derivative term to limit the high-frequency gain and noise. Derivative action is seldom used in practice though – by one estimate in only 25% of deployed controllers[citation needed] – because of its variable impact on system stability in real-world applications.
  
 The difference in a bad PID and a good PID is only shown at the K terms.
 
