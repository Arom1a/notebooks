## 1 Current
$$\vec I=\frac{\Delta q}{\Delta t}=neAv$$, where $n$ is the number of free electric charge in the conductor, $e$ is the charge of each electric charge, $A$ is the cross-section area of the conductor, and $v$ is the velocity of the electric charge in the conductor.

## 2 Resistance
The determining formula: $$R = \rho\frac{l}{A}$$, where $\rho$ is the resistivity, $l$ is the length, $A$ is the cross-sectional area.

Resistor in series:
- $I_{total}=I_1=I_2=I_3=\dots$
- $U_{total}=U_1+U_2+U_3+\dots$
- $I_{total}R_{total}=I_1R_1+I_2R_1+I_3R_1+\dots$
- $R_{total}=R_1+R_2+R_3+\dots$

Resistor in parallel:
* $I_{total}=I_1+I_2+I_3+\dots$
* $U_{total}=U_1=U_2=U_3=\dots$
* $I_{total}R_{total}=I_1R_1+I_2R_2+I_3R_3+\dots$
* $\frac{1}{R_{total}}=\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}+\dots$

## 3 Ohm's Law
$$I = \frac{U}{R}$$

## 4 Electric Power
$$P = I^2R = IU = \frac{U^2}{R}$$

## 5 Capacitance
$$C = \frac{Q}{V} = \frac{\epsilon_0 A}{d}$$, where $\epsilon_0$ is the permittivity of vacuum ($\epsilon_0 = \pu{8.854187817\cdot10^{-12} F/m}$).

The potential difference between two plates: $$V = E\cdot d$$

If there is medium between the plates: $$C = \frac{\kappa\epsilon_0A}{d}$$, where $\kappa$ is the dielectric constant of the medium.

Energy in a capacitor: $$E_P = \frac{1}{2}CV^2 = \frac{1}{2}\frac{Q^2}{C} = \frac{1}{2}QV$$

Capacitor in series:
* $Q_{total}=Q_1=Q_2=Q_3\dots$
* $U_{total}=U_1+U_2+U_3\dots$
* $\frac{Q_{total}}{U_{total}}=\frac{Q_1}{U_1}+\frac{Q_2}{U_2}+\frac{Q_3}{U_3}+\dots$
* $\frac{1}{C_{total}}=\frac{1}{C_1}+\frac{1}{C_2}+\frac{1}{C_3}+\dots$

Capacitor in parallel:
* $Q_{total}=Q_1+Q_2+Q_3\dots$
* $U_{total}=U_1=U_2=U_3\dots$
* $C_{total}U_{total}=C_1U_1+C_2U_2+C_3U_3+\dots$
* $C_{total}=C_1+C_2+C_3+\dots$

## 6 Inductance
$$L=\frac{\phi}{I}$$

## 7 Kirchhoff's Law
### 7.1 Kirchhoff's First Law (Junction Rule)
At any junction point, $$\sum{I_{\text{in}}} = \sum{I_{\text{out}}}$$

This law is deduced from the conservation of charge.

### 7.2 Kirchhoff's Second Law (Loop Rule)
Around any closure loop, $$\sum{\Delta{U}} = 0$$

This law is deduced from the conservation of energy.

## 8 RC Circuit
![[RC_circuit.png | 500px]]

Time constant: $$\tau = RC$$

Charging voltage across the capacitor: $$V_C = \epsilon\cdot (1-e^{-\frac{1}{RC}t})$$

Discharging voltage across the capacitor: $$V_D = \epsilon\cdot e^{-\frac{1}{RC}t}$$

Charging current: $$I = \frac{\epsilon}{R}e^{-\frac{1}{RC}t}$$

Discharging current: $$I = \frac{\epsilon}{R}e^{-\frac{1}{RC}t}$$

Half-full time: $$t = RC\cdot \ln{2}$$

## 9 LC Circuit
$$I = I_0 \cdot (1 - e^{-\frac{1}{L/R}t})$$

Time constant: $$\tau = \frac{L}{R}$$

![[lc_circuit.jpg]]
