## 9. Vertical Throw with Drag

---

## 🔹 Given

Equation of motion:

m dv/dt = −mg − k v  

Initial conditions:
- v(0) = v0  
- x(0) = 10 m  

---

## 🟢 Part A: Solve the Equation

### Step 1: Rearrange

dv/dt = −g − (k/m) v  

---

### Step 2: Solve (first-order linear ODE)

Solution for velocity:

v(t) = (v0 + (mg/k)) · e^(−(k/m)t) − (mg/k)

---

### Step 3: Position (integrate velocity)

x(t) = 10  
+ (m/k)(v0 + mg/k)(1 − e^(−(k/m)t))  
− (mg/k)t  

---

### ✅ Result:
Velocity and position are **exponential functions due to drag**

---

## 🟢 Part B: Maximum Height

Maximum height occurs when:

v(t) = 0  

---

### Step 1: Solve for time

0 = (v0 + mg/k)e^(−(k/m)t) − mg/k  

e^(−(k/m)t) = (mg/k) / (v0 + mg/k)

---

### Step 2: Solve for t_max

t_max = (m/k) · ln((v0 + mg/k) / (mg/k))

---

### Step 3: Substitute into x(t)

Height can be found by plugging t_max into x(t)

---

### ✅ Key Idea:
Maximum height is **less than no-drag case** due to energy loss

---

## 🟢 Part C: Comparison (No Drag)

Without drag:

v(t) = v0 − g t  

Maximum height:

h = v0² / (2g)

---

### ✅ Comparison:

| Case | Behavior |
|------|--------|
| No drag | Symmetric motion, higher peak |
| With drag | Slower rise, lower peak |
| Reason | Energy lost to air resistance |

---

## 🟢 Part D: Numerical Simulation (Python)

```python
import numpy as np
import matplotlib.pyplot as plt

# Parameters
m = 1.0
g = 9.8
k = 0.5
v0 = 20
x0 = 10

dt = 0.01
t_max = 5

t = np.arange(0, t_max, dt)
v = np.zeros(len(t))
x = np.zeros(len(t))

v[0] = v0
x[0] = x0

# Euler method
for i in range(len(t)-1):
    a = -g - (k/m)*v[i]
    v[i+1] = v[i] + a*dt
    x[i+1] = x[i] + v[i]*dt

# Plot
plt.plot(t, x)
plt.xlabel("Time (s)")
plt.ylabel("Height (m)")
plt.title("Vertical Motion with Drag")
plt.grid()
plt.show()
