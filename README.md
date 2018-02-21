# hw_pendulum
Homework for Garcia Ch. 2, pendulum

<div class="content">

## Contents

<div>

*   [Problem 1 (in class)](#2)
*   [Problem 2 (in class)](#3)
*   [Problem 3 (homework)](#4)

</div>

## Problem 1 (in class)<a name="2"></a>

Modify the MATLAB program <tt>pendul.m</tt> such that it includes the option to use the Leap-Frog method. Compare the results for the different methods for a simulation of 300 steps with a time step size of 0.1 sec.

## Problem 2 (in class)<a name="3"></a>

Modify pendul.m to display your results for *θ* vs. *t*, *ω* vs. *t*, and *ω* vs. *θ* as subplots similar to the format shown below, and add an update for the angular velocity (*ω*) for the Verlet method.

Comment: The figure was produced running 1000 time steps with the Verlet method, for *θ*<sub>0</sub> = 160° and with a time step size of *τ* = 0.1 sec. 

## Problem 3 (homework)<a name="4"></a>

Modify <tt>pendul.m</tt> to include a velocity-dependent damping term, such that the equation of motion for the pendulum is described by:

<a href="http://www.codecogs.com/eqnedit.php?latex=\dpi{300}&space;\large&space;\frac{d^2\theta}{dt^2}&space;=&space;-\gamma\omega&space;-&space;\frac{g}{L}\sin\theta" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\dpi{300}&space;\large&space;\frac{d^2\theta}{dt^2}&space;=&space;-\gamma\omega&space;-&space;\frac{g}{L}\sin\theta" title="\large \frac{d^2\theta}{dt^2} = -\gamma\omega - \frac{g}{L}\sin\theta" height=50 /></a>
 
where *γ* is the damping constant. Also, modify the program to terminate the simulation after the mechanical energy (i.e. potential + kinetic energy) is less than five percent of the original mechanical energy. Run the program with Verlet method for the following conditions:
 * *θ*(0) = 175°
 * *ω*(0) = 5 rad/s
 * *τ* = 0.02 s (time step size)
 * *γ* = 0.1 (damping coefficient)

Display plots of *θ* vs. *t*, *ω* vs. *t*, and *ω(t)* vs. *θ(t)* as in Problem 2.

</div>
