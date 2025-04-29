# csci2202---lab-7-floats-errors-and-plotting-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 – Lab 7 Floats, Errors and Plotting Solved](https://www.ankitcodinghub.com/product/csci2202-lab-7-floats-errors-and-plotting-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116965&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 - Lab 7 Floats, Errors and Plotting Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Carry out the following in IDLE: 7.8+0.2+8.9−2.1. What is the answer from Python? What is the exact answer? To get to the bottom of this, compute the machine epsilon: M.

Defn: M, is the smallest float, which added to 1, gives a float greater than 1.

Write a program to compute M. Start with = 1. In each iteration of the loop, halve M, add it to 1 and test the result. If the result is different from 1, continue looping.

2. Floating point operations need to be done with care. An example of a simple computation when things go awry: The Verhulst equation arises from population modelling studies Here we examine compute with the Verhulst equation in two ways: (We will explore this equation in later labs).

p(n + 1) = p(n) + r · p(n) · (1 − p(n))

• Evaluate the equation in two ways: (i) As written above.

(ii) p(n + 1) = (1 + r) · p(n) − r · p(n)2.

Use r = 3 and use p(0) = 0.01 as the initial condition. Print the two columns side-by-side with their difference in the third column.

• Formatted printing. Formatting floats, allows us to specify the number of digits before and after the decimal point: The new version of the format string for floats in Python:

Assume p, q are floats declared in your program. The formatted string: print(’p is : {0:12.10f}, q is: {1:8.3f}’.format(p, q)) prints argument 0 (p) in 12 digits with 10 digits after the decimal and argument 1 (q) with 8 digits, 3 of them after the decimal. The ‘f’ tells the interpreter to print the number as a ’float’

Print p(n) calculated the two ways specified with 12 digits after the decimal. When (i.e. at what iteration) do the values start to differ? Run your program for 50 iterations and observe the difference in the two output answers.

The point of this exercise is that the interactions of the slight round-off errors in floating points can be magnified by propagation of the error.

3. In this lab exercise you will re-visit projectile motion (motion in 2-D), plotting the trajectory with a slightly different method.

The vector equations of motion governing the projectile are:(a – acceleration, v(t) – velocity; s – displacement, t – time):

(1)

(2)

The motion resolved into components is:

x-component y-component

vx = v0 ∗ cosθ + ax ∗ t vy = v0 ∗ sinθ + ay ∗ t

x = x0 + v0 ∗ cosθ ∗ t + (1/2) ∗ ax ∗ t2

The Method:

Use numpy for the following exercise. To use numpy, first:

import numpy as np

import matpoltlib.pyplot as plt

Now any numpy functions can be used, for example: np.cos(x*np.pi). numpy has its own library of functions. In the program use the functions from the numpy module. https://numpy.org/doc/stable/reference/routines.math.html

(a) Choose a time interval ∆t (a value in the range 0.01 to 0.05) and define the initial values of x,y,vx,vy,t. Start the projectile off at (−200,0) with a specified initial velocity and angle.

(b) Choose N – the maximum number of intervals (this gives the max. time : tmax = N ∗ ∆t for the numerical solution). So at the kth time-step: tk = k ∗ ∆t. Experiment with various values for N and ∆t, to find a suitable plot for the trajectory ( as an estimate tmax ≈ 2 ∗ v0/g).

(c) Note that acceleration is a constant and only acts in the −y direction (i.e. ax = 0 &amp; ay = −g)

(d) Start by setting the current position to the initial position x = −200,y = 0; with current velocity components to the initial velocity components vx = v0x, vy = v0y.

(e) Store the initial values of x,yt in numpy arrays.. Also store v0x and v0y in arrays. (see the previous lab for numpy arrays).

(f) Next, iterate (loop) over the next 4 steps, repeating the steps while n &lt; N (or alternatively t &lt; tmax). A convenient way to do this is to use the range function in the form range(1, N+1).

(See: https://docs.python.org/3/library/functions.html#func-range).

(g) Compute the new velocity components at a time ∆t later: vx + ∆vx = vx + ax ∗ ∆t &amp; vy + ∆vy = vy + ay ∗ ∆t

(The ∆s here indicate change in the variable. For ex. above, ∆vx = ax∗∆t. You have chosen a value for ∆t. The same holds for the ∆’s below) (h) Compute the new position coordinates at a time ∆t later:

&amp; .

(i) Store the new t,x,y values and the new vx,vy values in the arrays.

(j) Set the current positions and velocities to the new positions and velocities and loop back to step (g) and repeat. (In effect, the x,y,vx,vy computed in each time-step become the initial value for the next time-step)

(k) Loop over the arrays and determine the max height the projectile reaches: yMax and the time (after the start) it reaches this height.

(l) Loop over the arrays and find the x distance the projectile travels (the range): xMax. This is the x value corresponding to the y value going to zero. Also print the time at which xMax is reached.

(m) Print the three arrays (t,x,y) side-by-side, formatted to have three digits to the left of the decimal point and three digits to the right of the decimal point. for example: ’{:6.3f}’.format(x[i]) will print x[i], as a float with 6 digits; 3 of them after the decimal.

(n) Plot y v/s x using matplotlib.pyplot. This is a sophisticated plotting package (see matplotlib.org).

A very basic plot is made by adding the following: (after the (x, y, t) arrays are computed).

• plt.plot(x, y, ’b-’) plots a (blue) line through the points (x,y) of the trajectory.

• plt.xlabel(“x”) labels the x axis and similarly plt.ylabel(“y”) the y axis.

• Finally, the last command must be plt.show().

• Examples are available at: https://matplotlib.org/3.1.0/tutorials/ introductory/pyplot.html
