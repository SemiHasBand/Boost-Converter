# Contents
- [2025/9/30](#2025930)

---

## 2025/9/30
The conventional ramp generator is composed of: V-I converter, current mirror, two hysteresis comparators, and one S-R latch circuit

The proposed ramp generator is composed of: V-I converter, current mirror, and Schmitt trigger circuit

First, I want to design a high-accuracy V-I converter.
The tech I am using involves an op-amp with a PMOS and a NMOS along with a source resistor. 
At the test 1, I set a 50Mohms resistor with NMOS W/L=1, L=1um, PMOS W/L=4, L=1um.
The results show that both PNMOS operates in subth.
Although operating points seems a bit concerning, if the corner and dc sweep is stable, it may still be acceptable for use.

Exp result: DC sweep is activate in 1.5 to 3V, all is correct(tt 25, ff -10, ss 110: 1.797, ff 110: 1.801, ss -10: 1.799)

