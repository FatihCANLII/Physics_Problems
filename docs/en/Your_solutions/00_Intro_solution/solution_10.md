## 10. Infinite Series

An ant starts at the origin \((0,0)\) and moves in the following pattern:

- \(1\) m east  
- \( \frac{1}{2} \) m north  
- \( \frac{1}{3} \) m west  
- \( \frac{1}{4} \) m south  
- \( \frac{1}{5} \) m east  
- and continues in the same pattern.

The directions repeat every four steps:

- **East**
- **North**
- **West**
- **South**

---

## Step 1: Separate the Horizontal and Vertical Motions

### Horizontal movement

The horizontal displacements are:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \frac{1}{9} - \cdots
$$

This is the **alternating harmonic series over odd numbers**.

It is known that:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots = \frac{\pi}{4}
$$

So the total **horizontal position** is:

$$
x = \frac{\pi}{4}
$$

---

## Step 2: Vertical Movement

The vertical displacements are:

$$
\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \frac{1}{10} - \cdots
$$

Factor out \( \frac{1}{2} \):

$$
\frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)
$$

The series inside the parentheses is the **alternating harmonic series**:

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln(2)
$$

Therefore,

$$
y = \frac{1}{2}\ln(2)
$$

---

## Step 3: Determine the Final Position

Combining the horizontal and vertical displacements gives the final coordinates:

$$
\left(\frac{\pi}{4}, \frac{1}{2}\ln(2)\right)
$$

---

## Final Answer

The ant approaches the position:

$$
\left(\frac{\pi}{4}, \frac{\ln(2)}{2}\right)
$$

Approximate numerical values:

- \(x \approx 0.785\)
- \(y \approx 0.347\)
