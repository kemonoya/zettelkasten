202405022024
Status: #idea
Tags: [[Mechanics]]

# Integral of the motion

Integrals of the motion are functions of the coordinates and velocities in the system that do not change with time, and depend only on the initial conditions. There are, for a system of $s$ degrees of freedom, exactly $2s-1$ integrals of the motion. This is illuminated by the following argument:

A solution for a system of $s$ degrees of freedom contains $2s$ arbitrary constants, and it is determined uniquely by our choice of those constants (by uniqueness of solutions to differential equations). Since closed systems do not depend on time explicitly, the origin of time is arbitrary and may always be taken as one of the arbitrary constants of the solution (we exclude time origin because it is not a function of the coordinates and velocities). That leaves $2s-1$ quantities. The equations of motion $a = \textbf F(\textbf x, \dot{\textbf x},t)$ ([[Newton's equations]]) define a [[Phase velocity vector field]] on the coordinate-velocity-time phase space that describes the phase of the mechanical system. Solutions to the equations of motion are the [[Integral curve]]s of this phase velocity vector field. By uniqueness of solutions to ordinary differential equations, there exists only one curve with the fitting initial conditions to give any specific choice of the $2s-1$ constants (origin of time again can be disregarded since the phase space is symmetric along $t$-axis translations. We're actually looking at families of curves, each family being the same curve repeated along the entire $t$-axis, and the family is then entirely determined by the $2s-1$ constants). So, we can write the $2s-1$ quantities as functions of the phase curve itself (i.e. as functions of $q$ and $\dot q$), and these functions give the same value at any point on that solution phase curve.

**UNCERTAIN about the eliminating $t-t_0$ part to be honest, need more thinking as to what that means. I think I'm close to getting it with the "looking at families of curves" part.**

___
# References
[[📕 Mechanics - Landau & Lifshitz]], pg.13.
[[📕 Ordinary Differential Equations - V.I. Arnold]], chs. 1, 2.