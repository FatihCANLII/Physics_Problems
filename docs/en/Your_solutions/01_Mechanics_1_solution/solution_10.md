Given:
r(t) = (a cos(ωt), b sin(ωt), bt)

---

## (a) Trajectory equation

From x and y:

x = a cos(ωt)  
y = b sin(ωt)

Eliminate t using identity:

(x/a)² + (y/b)² = cos²(ωt) + sin²(ωt) = 1

So:

(x²/a²) + (y²/b²) = 1

and:

z = bt  ⇒  t = z/b

Thus, the trajectory is an **elliptical helix**:

(x²/a²) + (y²/b²) = 1,  z = bt

---

## (b) Path length

Velocity:

v(t) = dr/dt  
= (-aω sin(ωt), bω cos(ωt), b)

Speed:

|v(t)| = √[a²ω² sin²(ωt) + b²ω² cos²(ωt) + b²]

Arc length:

s = ∫₀^{t₀} |v(t)| dt  

So:

s = ∫₀^{t₀} √[a²ω² sin²(ωt) + b²ω² cos²(ωt) + b²] dt

(This generally does **not simplify nicely** unless special cases apply.)

---

## (c) Python visualization

```python
import numpy as np
import matplotlib.pyplot as plt

# parameters
a = 2
b = 1
w = 1
t = np.linspace(0, 10, 500)

x = a * np.cos(w * t)
y = b * np.sin(w * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(projection='3d')

ax.plot(x, y, z)
ax.set_xlabel('x')
ax.set_ylabel('y')
ax.set_zlabel('z')

plt.show()
