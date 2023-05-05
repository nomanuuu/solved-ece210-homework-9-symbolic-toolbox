Download Link: https://assignmentchef.com/product/solved-ece210-homework-9-symbolic-toolbox
<br>
In this (final) problem set, you will review the symbolic toolbox and create a simple app using the app designer.

1.    Consider the system of differential equations:

Solve the system using the symbolic toolbox’s dsolve function using four different initial conditions (so you should have four sets of solutions):

x(0) = −1, y(0) = 1 x(0) = 1, y(0) = 1

x(0) = −1, y(0) = −1

x(0) = 1, y(0) = −1

Then plot all four parametric curves (x(t),y(t)) on the same plot on t = [0 100] using fplot. This should generate four spirals. Use a legend.

2.    Consider the following experiment: You roll M D-sided fair die, and count the sum of all the die values.

You are going to build an app using appdesigner that displays a histogram of the resulting sums. There should be input boxes to control the simulation, a button to run the simulation, and a plot plane (UIAxes) to plot the histogram. You will need three input boxes: one for M, one for D, and one for the number of simulations to run, N. Make each bin width 1, and normalize the counts (see the histogram “BinWidth” and “Normalization” options). (You can assume that the input is valid.)

For submission, export the app to a .m file by clicking Save &gt; Export to .m File, and make sure you can run it like you would a normal function. (E.g., if you export your app to dice_sim.m, you should be able to call it by running dice_sim.)

(As M increases, the distribution becomes more normal – this is a demonstration of the Central Limit Theorem.)

1