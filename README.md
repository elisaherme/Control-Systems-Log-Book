# Control Systems Practicals
##Practical 1 30/01/2017
###Task 1
![](https://cloud.githubusercontent.com/assets/25483756/22626061/8ddd8d14-eb9c-11e6-834a-093a02012252.png)

###Task 2

####Sinusoidal amplitude= 1 frequency= 20

![](https://cloud.githubusercontent.com/assets/25483756/22626067/f80a0816-eb9c-11e6-81b6-98a70ca519ad.png)

####The signal both output and input are sinusoids. Property of LTI system. A sinusoid signal produces a sinusoidal signal with delay. There’s a phase difference.

####Square wave

![](https://cloud.githubusercontent.com/assets/25483756/22626108/ed9061cc-eb9d-11e6-8ef8-924ee51c466c.png)

####Replacing signal generator with step input
![](https://cloud.githubusercontent.com/assets/25483756/22626109/f33e3e46-eb9d-11e6-9c11-4080a7db78b5.png)
![](https://cloud.githubusercontent.com/assets/25483756/22626111/f6ecfafa-eb9d-11e6-8e95-0ecee426d6f6.png)

####If we evaluate the roots in the denominator, we can get different outputs depending on how the imaginary and real part are:

*	Negative real part, stable system
* Positive real part, unbounded unstable, it goes to infinity
* Zero real part, oscillate forever (imaginary axis)

####If the denominator is 0, then the output would go to infinity. As we want an unstable response, we want positive real part of the roots. If at least one of the poles are positive, then it is unstable. For stable system you require the poles to be negative. We want to create an unstable system. We can put -70s so the positive part turns positive.

###Task 3
![](https://cloud.githubusercontent.com/assets/25483756/22626093/97208e98-eb9d-11e6-87c3-4658cf81fa25.png)

####Frequency= 1 amplitude=1 
####It is BIBO stable 
####Yellow line = output, it is the sum of a lot of sinusoidal waves
####Blue line = input

![](https://cloud.githubusercontent.com/assets/25483756/22626107/d8f22a3e-eb9d-11e6-8d91-f120b68a9840.png)

###Task 4
![](https://cloud.githubusercontent.com/assets/25483756/22626102/b7e4c888-eb9d-11e6-9690-45fb833a173d.png)
![](https://cloud.githubusercontent.com/assets/25483756/22626098/ae38764a-eb9d-11e6-9604-c246f17f221f.png)

####In the previous result, the roots had a real part.

####The roots of the denominator of the transfer function are purely imaginary so it is bounded and it doesn’t go to infinity and oscillates forever. Giving a bit of energy (step input) makes the system oscillates. 

####In mass spring system, it’s like holding the mass and then release it. Without any sort of resistance (air) and a perfect spring, the mass would keep oscillating in the same way forever.

###Task 5

####Mass spring damper system
![](https://cloud.githubusercontent.com/assets/25483756/22626103/c3f61ffa-eb9d-11e6-8b0e-3aa8adec5406.png)

####Instead of having oscillatory solution, we have damped oscillation. We want a better response. Overshoot (Mp) is amplitude of biggest (first peek).
####We want to decrease the overshoot and force the system to reach a steady state value.

![](https://cloud.githubusercontent.com/assets/25483756/22626104/c7af973e-eb9d-11e6-9bab-d9babfd7393c.png)
