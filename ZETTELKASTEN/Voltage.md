202405072108
Status: #idea
Tags: [[Circuit analysis]]

# Voltage

*Voltage* (also called the *potential difference*) between two points of a circuit is defined as the potential energy needed to transfer a unit charge from the first point to the second. Or equivalently, the potential energy lost in transferring a unit charge between the two points. Mathematically, this means
$$\Delta V = \frac{\Delta U}{q} \hspace{0.2cm}\text{ or }\hspace{0.2cm}V_{AB}=V_{A}-V_{B}=\frac{U_{A}-U_{B}}{q},$$
where $U$ is the [[Potential energy at a point of a conductor]], direction of current is assumed to be the conventional direction and test charges $q$ are assumed positive. It is measured in $\text{Joule}/\text{Coulomb}$, more commonly named a $\text{Volt}$. The formula above is read as
$$\text{voltage drop from A to B} = \frac{\text{energy lost in transferring charge } q \text{ from A to B}}{\text{charge }q}.$$

A voltage must exist between two points of a circuit to get electrical [[Current]] to flow between them. In other words, when a voltage exists between two terminals of a conductor (such as a wire), an *[[Electromotive force]]* (EMF) is generated which pushes the electrons along and gives rise to the current. Thinking of EMFs is a more practical way to visualize voltages than using the definition given above.

As we track the potential energy at points through a *load* (resistor, lamp, etc.), we'll find that its potential energy decreases as we go across the terminals of the load. This is because as electrons go through the load, some of their potential energy is lost from the collisions with other electrons, or with lattices of conductor atoms (in the form of heat, light, etc.) and so the "electrical pressure" they exert on the electrons around them becomes lower, the further down the load they are (see figure below). As a result of this, there arises a difference between the two terminals of the load; a *voltage*, or *voltage drop*, as we call it. 


![[voltage_drop.png]]

There is, to a good approximation, no loss in the potential energy of an electron when it transfers from one point of a conductor (wire) to another point of the same conductor. Voltage drop only happens across a load. In other words, the voltage between two points of the same conductor is zero.

___
# References
[[📕 Practical Electronics for Inventors - Scherz & Monk]], pgs. 9-14.