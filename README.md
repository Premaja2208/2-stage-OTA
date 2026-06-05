# 2-Stage Op-Amp Design using 180nm Technology

Design and layout implementation of a high-performance two-stage operational amplifier using 180nm semiconductor technology. The design achieves the required gain, bandwidth, and power efficiency through simulation and characterization.

---

## Circuit Diagram

<img width="1916" height="950" alt="image" src="https://github.com/user-attachments/assets/e613f0ba-37b1-4659-9008-3cb517ff214f" />


---

## Design Specifications

- Vdd = 1.8V  
- DC Gain = 60 dB  
- GBW = 5 MHz  
- Phase Margin ≥ 60°  
- Slew Rate = 10 V/µs  
- ICMR (+) = 1.6V  
- ICMR (−) = 0.8V  
- Load Capacitance (CL) = 10 pF  
- Compensation Capacitor (Cc) ≥ 3 pF  
- Power Dissipation = 170 µW  

---

## Design Process

- (W/L) ratio of M3, M4 is determined using ICMR (+)  
- (W/L) ratio of M1, M2 is determined using GBW  
- Tail current (I5) is calculated using slew rate  
- (W/L) ratio of M5 is determined using ICMR (−)  
- (W/L) ratio of M6 is chosen based on zero location for stability  

---

## Technology Used

- LTspice (tsmc018.lib)
