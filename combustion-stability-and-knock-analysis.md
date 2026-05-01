# 4.0 Combustion Stability and Knock Analysis

---

## 4.1 Introduction

Combustion stability refers to an engine's ability to maintain a consistent and controlled heat release rate during combustion.

In the PNG Energy System, combustion stability is treated as a **pre-combustion phenomenon**, governed primarily by:
- Fuel atomization quality  
- Mixture homogeneity  
- Injection timing dynamics  

---

## 4.2 Knock Formation Mechanism (Thermo-Kinetic Model)

Knock occurs when the unburned end-gas auto-ignites before the flame front arrives.

### 4.2.1 Knock Condition

$$
\tau_{ign} < \tau_{flame}
$$

Where:
- \( \tau_{ign} \) = ignition delay time  
- \( \tau_{flame} \) = flame propagation time  

---

### 4.2.2 Ignition Delay Model (Arrhenius Form)

$$
\tau_{ign} = A p^{-n} e^{\frac{E_a}{RT}}
$$

Where:
- \( A \) = constant  
- \( p \) = pressure  
- \( n \) = pressure exponent  
- \( E_a \) = activation energy  
- \( R \) = gas constant  
- \( T \) = temperature  

---

## 4.3 Flame Propagation Behavior

Flame propagation determines combustion uniformity and energy release rate.

$$
S_L \propto \sqrt{\alpha \cdot \frac{Q}{T}}
$$

Where:
- \( S_L \) = laminar flame speed  
- \( \alpha \) = thermal diffusivity  
- \( Q \) = heat release rate  

---

## 4.4 Pressure Wave Dynamics

Knock is a resonant pressure oscillation inside the combustion chamber.

$$
p(t) = p_0 + \Delta p \sin(\omega t)
$$

Where:
- \( p_0 \) = mean pressure  
- \( \Delta p \) = pressure fluctuation amplitude  
- \( \omega \) = oscillation frequency  

---

## 4.5 Solved Examples

### Example 1: Knock Condition Check

Given:
- \( \tau_{flame} = 2.5 ms \)  
- \( \tau_{ign} = 1.8 ms \)

Solution:

Since:
$$
\tau_{ign} < \tau_{flame}
$$

**Result:** Knock occurs.

---

### Example 2: Atomization Effect

Case A (coarse droplets):
- \( \tau_{ign} = 3.0 ms \)
- \( \tau_{flame} = 2.8 ms \)

→ Knock likely

Case B (fine droplets):
- \( \tau_{ign} = 4.2 ms \)
- \( \tau_{flame} = 4.0 ms \)

→ Stable combustion

**Conclusion:** Improved atomization reduces knock risk.

---

## 4.6 Engineering Diagram

### 4.6.1 Conceptual Illustration

The following figure compares normal combustion and knocking phenomena inside a cylinder.

---

###  Figure 4.1: Normal Combustion vs Knock

![Combustion Stability and Knock Analysis](https://raw.githubusercontent.com/iwerieborjoseph002-cloud/Png_energy_system/main/49f65f1f91514f860b64fced4f67f75cf968e64247f99407ce967fed4cd36a06.png)

---

### 4.6.2 Figure Description

**Left: Normal Combustion**
- Uniform air–fuel mixture  
- Single flame front propagation  
- Smooth pressure rise  

**Right: Knock Condition**
- End-gas auto-ignition zones  
- Multiple ignition points  
- Shock wave formation  
- Pressure oscillations  

**Key components:**
- Spark plug  
- Flame front  
- End-gas region  
- Pressure waves  
- Cylinder wall reflections  

---


## 4.7 PNG Energy System Interpretation

Knock is fundamentally a **time-scale mismatch problem**:

- Chemical ignition delay vs flame propagation time  
- Controlled by mixture quality rather than ignition timing alone  

Improved atomization leads to:
- Faster evaporation  
- Homogeneous mixture  
- Reduced hot spots  
- Stable combustion  

---

## 4.8 Engineering Insight

Combustion stability improves when:
- Ignition delay is controlled  
- Flame propagation is uniform  
- Pressure oscillations are minimized  

---

## 4.9 Conclusion

Knock is a coupled thermodynamic and kinetic instability caused by:
- premature auto-ignition  
- uneven mixture formation  
- pressure wave resonance  

The PNG Energy System reduces knock by optimizing **pre-combustion fuel–air preparation**, not only ignition timing.



