202405052134
Status: #idea
Tags: [[Mechanics]]

# Angular momentum

A [[Conserved quantity]] in closed mechanical systems. It has the form
$$\textbf M = \sum\limits \textbf r_{a}\times \textbf p_a,$$
where the sum is over the particles in the system, and $\textbf p_a$ is the [[Momentum]] of the individual particles. We can see by definition that the angular momentum is additive for particles in the system regardless of whether or not they interact, much like the momentum.

The angular momentum (or components of it) may be conserved in systems that move in external fields, if the field is symmetric about some axis. Evidently, rotation about that axis leaves the system unaffected, so the component of angular momentum along that axis is conserved. An important example of this is that of a central field, in which the potential depends only on the distance from a center. In such a field, all components of angular momentum are conserved if we take the origin to be at the center of the field, as any rotation about an axis going through the center leaves the system unaffected.

The component of angular momentum about any axis may be extracted from the [[Lagrangian]] by differentiating it with respect to the corresponding angular velocity. For example, the component of angular momentum along the $z$-axis is
$$\textbf M_{z} = \sum\limits_a\frac{\partial L}{\partial \dot \varphi_a},$$
where $\varphi$ is the angle of rotation about the $z$-axis, and the sum is over all particles in the system. To see why this is, consider the following: if we're rotating about the $z$-axis, the angular velocities $\dot \varphi_a$ are unaffected, since their vectors point in the direction of the $z$-axis. Hence, the only quantities changing in the rotation are the angles $\varphi_a$. Therefore, since the Lagrangian is unaffected by the rotation, we can say (by writing the Lagrangian in polar coordinates, varying only the angles $\varphi_a$ and setting the first-order expansion equal to 0)
$$\sum\limits_a \frac{\partial L}{\partial \varphi_a} = 0.$$
This, by the Euler-Lagrange equations, is the same as
$$\frac{d}{dt}\sum\limits_a\frac{\partial L}{\partial \dot \varphi_a} = 0,$$
which coincides with the form of the conservation of angular momentum. Hence, we can define the angular momentum as
$$\textbf{M}_z \equiv \sum\limits_a \frac{\partial L}{\partial \dot \varphi_a}.$$

___
# References
[[📕 Mechanics - Landau & Lifshitz]], pgs. 18-21.