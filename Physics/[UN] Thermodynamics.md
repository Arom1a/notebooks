For monoatomic molecules: $C_V=\frac{3}{2}R$
For biatomic molecules: $C_V=\frac{5}{2}R$
For triatomic molecules: $C_V=\frac{7}{2}R$

For all molecules: $C_P=C_V+R$

Standard temperature and pressure: $\pu{273.15 K}$, ${1.01325 \times 10^{15} Pa}$ (or $\pu{1 atm}$)

## 1 Laws of Thermodynamics
### 1.1 First Law
$$\Delta{U} = Q - W$$, where $\Delta{U}$ is the change of internal energy, $Q$ is the heat transferred to the system, $W$ is the work done by the system.

### 1.2 Second Law
Heat always flows downhill spontaneously from hotter to colder regions of matter.

Entropy can only increase overall.

## 2 Thermodynamic Processes
### 2.1 Isochoric process
Also called isometric process, and isovolumetric process.
$\Delta{V} = 0$
During the isochoric process, the volume is unchanged.
$W = P\Delta{V} = 0$
$Q_V = nC_V\Delta{T}$
$\Delta{U} = Q - W = Q_V$

### 2.2 Isobaric process
$\Delta{p} = 0$
During the isobaric process, the pressure is unchanged.
$W = P\Delta{V} = nR\Delta{T}$
$Q_P = nC_P\Delta{T}$
$\Delta{U} = Q - W = nC_V\Delta{T}$

### 2.3 Isothermal process
$\Delta{T} = 0 \to \Delta{U} = 0$
During the isothermal process, the temperature is unchanged.
$W = nRT\ln{\frac{V_f}{V_i}} = P_iV_i\ln{\frac{V_f}{V_i}} = P_fV_f\ln{\frac{V_f}{V_i}}$
$Q = W$

### 2.4 Adiabatic process
$Q = 0$
During the adiabatic process, there is no exchange of heat.
$W = -nC_V(T_f-T_i) = -\frac{C_V}{R}(P_fV_f - P_iV_i)$

$P_1V^{\frac{C_P}{C_V}}_1=P_2V^{\frac{C_P}{C_V}}_2$
$\frac{C_P}{C_V}$ is called **adiabatic index**

Isobaric Q > Isochoric Q > Isothermal Q > Adiabatic Q

## 3 Heat Engine
### 3.1 Carnot engine
1. Isothermal expansion
	$P \downarrow V \uparrow U \rightarrow$
2. Adiabatic expansion
	$P \downarrow V \uparrow U \downarrow$
3. Isothermal compression
    $P \uparrow V \downarrow U \rightarrow$
4. Adiabatic compression
    $P \uparrow V \downarrow U \uparrow$

### 3.2 Maximum possible efficiency
$$\eta = 1 - \frac{T_C}{T_H}$$, where $T_C$ is the temperature of the cold source, $T_H$ is the temperature of the hot source.
