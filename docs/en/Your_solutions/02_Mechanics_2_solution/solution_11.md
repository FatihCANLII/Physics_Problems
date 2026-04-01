## 11. Dynamics with a Time-Dependent Force

---

## 🔹 Given

- Mass: m = 3 kg  

Force:

F(t) = (15t, 3t − 12, −6t²)

Initial conditions:
- r0 = (5, 2, −3)  
- v0 = (2, 0, 1)  

---

## 🟢 Part A: Acceleration

Use Newton’s second law:

a = F / m  

---

### Compute components:

ax = (15t) / 3 = 5t  
ay = (3t − 12) / 3 = t − 4  
az = (−6t²) / 3 = −2t²  

---

### ✅ Result:

a(t) = (5t, t − 4, −2t²)

---

## 🟢 Part B: Velocity

Velocity = integral of acceleration

---

### x-component:

vx = ∫ 5t dt = (5/2)t² + C1  

Use v0x = 2:

2 = (5/2)(0)² + C1 → C1 = 2  

vx = (5/2)t² + 2  

---

### y-component:

vy = ∫ (t − 4) dt = (1/2)t² − 4t + C2  

Use v0y = 0:

0 = 0 + C2 → C2 = 0  

vy = (1/2)t² − 4t  

---

### z-component:

vz = ∫ (−2t²) dt = −(2/3)t³ + C3  

Use v0z = 1:

1 = 0 + C3 → C3 = 1  

vz = −(2/3)t³ + 1  

---

### ✅ Result:

v(t) = ((5/2)t² + 2, (1/2)t² − 4t, −(2/3)t³ + 1)

---

## 🟢 Part C: Position

Position = integral of velocity

---

### x-component:

x = ∫ [(5/2)t² + 2] dt  
x = (5/6)t³ + 2t + C4  

Use x0 = 5:

5 = 0 + C4 → C4 = 5  

x(t) = (5/6)t³ + 2t + 5  

---

### y-component:

y = ∫ [(1/2)t² − 4t] dt  
y = (1/6)t³ − 2t² + C5  

Use y0 = 2:

2 = 0 + C5 → C5 = 2  

y(t) = (1/6)t³ − 2t² + 2  

---

### z-component:

z = ∫ [−(2/3)t³ + 1] dt  
z = −(1/6)t⁴ + t + C6  

Use z0 = −3:

−3 = 0 + C6 → C6 = −3  

z(t) = −(1/6)t⁴ + t − 3  

---

### ✅ Result:

r(t) = ( (5/6)t³ + 2t + 5,  
         (1/6)t³ − 2t² + 2,  
         −(1/6)t⁴ + t − 3 )

---

## 📌 Summary

| Quantity | Expression |
|----------|----------|
| Acceleration | (5t, t − 4, −2t²) |
| Velocity | ((5/2)t² + 2, (1/2)t² − 4t, −(2/3)t³ + 1) |
| Position | ((5/6)t³ + 2t + 5, (1/6)t³ − 2t² + 2, −(1/6)t⁴ + t − 3) |

---
