# Control Systems Practicals

##Task 1

##Task 2

####Sinusoidal amplitude= 1 frequency= 20

####The signal both output and input are sinusoids. Property of LTI system. A sinusoid signal produces a sinusoidal signal with delay. There’s a phase difference.

####Square wave

####Replacing signal generator with step input

####If we evaluate the roots in the denominator, we can get different outputs depending on how the imaginary and real part are:

*	Negative real part, stable system
* Positive real part, unbounded unstable, it goes to infinity
* Zero real part, oscillate forever (imaginary axis)

####If the denominator is 0, then the output would go to infinity. As we want an unstable response, we want positive real part of the roots. If at least one of the poles are positive, then it is unstable. For stable system you require the poles to be negative. We want to create an unstable system. We can put -70s so the positive part turns positive.

##Task 3

####Frequency= 1 amplitude=1 
####It is BIBO stable 
####Yellow line = output, it is the sum of a lot of sinusoidal waves
####Blue line = input

##Task 4

####In the previous result, the roots had a real part.

####The roots of the denominator of the transfer function are purely imaginary so it is bounded and it doesn’t go to infinity and oscillates forever. Giving a bit of energy (step input) makes the system oscillates. 

####In mass spring system, it’s like holding the mass and then release it. Without any sort of resistance (air) and a perfect spring, the mass would keep oscillating in the same way forever.

##Task 5

####Mass spring damper system

####Instead of having oscillatory solution, we have damped oscillation. We want a better response. Overshoot (Mp) is amplitude of biggest (first peek).
####We want to decrease the overshoot and force the system to reach a steady state value.
