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
