# Morris-Lecar-Model
  This project replicate some figures in the Morris-Lecar Model paper. 
  In this project, the membrane potential of barnacle giant muscle fibers was simulated under various conditions using the Morris-Lecar Model. Complex voltage behaviors were observed in the muscle's simple conductance system, which consists of only two types of non-inactivating voltage-dependent channels: voltage-dependent Ca2+ and K+ channels. Initially, the voltage behavior of the all-K+ condition was effectively simulated by setting gCa to 0, which exhibited the K+ resting behavior. Furthermore, the Ca2+ plateau behavior of the all-Ca2+ condition (gK = 0) was successfully simulated using a nonlinear driving force expression that considered the electrodiffusion of Ca2+ ions. Additionally, different types of oscillations, such as damped and limit cycle oscillations, were effectively simulated when both Ca2+ and K+ channels were present. A phase diagram was generated to illustrate the limit cycle and damped oscillations. 
  The second part of this project aimed to investigate the effects of various parameters on voltage behavior. To simplify the analysis, the Ca2+ system was assumed to be much faster than the K+ system (i.e., assumes M = M∞), resulting in a reduced V, N system (i.e., a system that only considers membrane potential V and K open probability N). The impact of different injected currents on the membrane potential successfully demonstrated how the system entered and exited oscillations. Isoclines of V_dot = 0 and N_dot = 0 were also successfully generated under various current conditions. One intersection of the V_dot = 0 and N_dot = 0 isoclines was shown to be an unstable node, leading to stable (limit cycle) oscillations. The real and imaginary parts of the eigenvalues of the linearized V, N-reduced system were also examined. According to the paper, stable limit cycle oscillations occurred when the current was adjusted to make the real part of the eigenvalue positive. The imaginary part of the eigenvalue indicated the oscillation frequency. This project successfully generated a plot of the real and imaginary parts of the eigenvalues by calculating the eigenvalues of the Jacobian matrix at the steady state (V_dot = 0 and N_dot = 0).

