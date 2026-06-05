# 3. Propagation of Error III

In this problem, the resistance is calculated using Ohm's Law. Since both the voltage and current have measurement uncertainties, the final resistance will also have an uncertainty.

The measured values are:

$$
V = (10.0 \pm 0.2)\text{ V}
$$

$$
I = (2.00 \pm 0.05)\text{ A}
$$

Our goal is to calculate the resistance and determine its uncertainty.

---

## Step 1: Calculate the Resistance

Using Ohm's Law:

$$
R = \frac{V}{I}
$$

Substituting the measured values:

$$
R = \frac{10.0}{2.00}
$$

$$
R = 5.00\Omega
$$

Therefore, the calculated resistance is:

$$
R = 5.00\Omega
$$

---

## Step 2: Calculate the Relative Uncertainty

Since resistance is calculated by dividing voltage by current, we use the uncertainty formula for division:

$$
\frac{\Delta R}{R}
=
\sqrt{
\left(\frac{\Delta V}{V}\right)^2
+
\left(\frac{\Delta I}{I}\right)^2
}
$$

Substituting the values:

$$
\frac{\Delta R}{R}
=
\sqrt{(0.02)^2+(0.025)^2}
$$

$$
\frac{\Delta R}{R}
=
0.032
$$
---

## Step 3: Calculate the Absolute Uncertainty

To obtain the absolute uncertainty in resistance:

$$
\Delta R = R \times \frac{\Delta R}{R}
$$

Substituting the values:

$$
\Delta R = 5.00 \times 0.032
$$

$$
\Delta R = 0.16\Omega
$$

---

## Final Result

The resistance is:

$$
R = 5.00\Omega
$$

The uncertainty is:

$$
\Delta R = 0.16\Omega
$$

Using standard uncertainty notation:

$$
\boxed{R = (5.00 \pm 0.16)\Omega}
$$

Therefore, the measured resistance is 5.00 Ω, and its possible variation due to measurement uncertainty is ±0.16 Ω.
