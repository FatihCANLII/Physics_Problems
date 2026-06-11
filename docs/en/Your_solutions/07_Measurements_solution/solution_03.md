# 3. Propagation of Error III

In this problem, the resistance is calculated using Ohm’s Law. Since both the voltage and current contain measurement uncertainties, the calculated resistance will also have an uncertainty.

The measured values are:

$$
V = (10.0 \pm 0.2)\text{ V}
$$

$$
I = (2.00 \pm 0.05)\text{ A}
$$

Our goal is to calculate the resistance and determine its uncertainty using uncertainty propagation.

---

## Step 1: Calculate the Resistance

Using Ohm’s Law:

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

## Step 2: Calculate the Partial Derivatives

To determine how uncertainties in voltage and current affect the resistance, we calculate the partial derivatives of:

$$
R(V,I)=\frac{V}{I}
$$

With respect to voltage:

$$
\frac{\partial R}{\partial V}
=
\frac{1}{I}
$$

With respect to current:

$$
\frac{\partial R}{\partial I}
=
-\frac{V}{I^2}
$$

These derivatives describe how sensitive the resistance is to changes in voltage and current.

---

## Step 3: Calculate the Uncertainty in Resistance

For independent measurements, uncertainty propagation is given by:

$$
\Delta R
=
\sqrt{
\left(
\frac{\partial R}{\partial V}\Delta V
\right)^2
+
\left(
\frac{\partial R}{\partial I}\Delta I
\right)^2
}
$$

Substituting the derivatives:

$$
\Delta R
=
\sqrt{
\left(
\frac{1}{I}\Delta V
\right)^2
+
\left(
-\frac{V}{I^2}\Delta I
\right)^2
}
$$

Now substitute the measured values:

$$
\Delta R
=
\sqrt{
\left(
\frac{1}{2.00}\times0.2
\right)^2
+
\left(
-\frac{10.0}{(2.00)^2}\times0.05
\right)^2
}
$$

Simplifying:

$$
\Delta R
=
\sqrt{
(0.10)^2
+
(0.125)^2
}
$$

$$
\Delta R
=
\sqrt{
0.01+0.015625
}
$$

$$
\Delta R
=
\sqrt{0.025625}
$$

$$
\Delta R
=
0.16\Omega
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
R = (5.00 \pm 0.16)\Omega
$$

Therefore, the measured resistance is expected to lie within the interval:

$$
4.84\Omega \leq R \leq 5.16\Omega
$$

This result shows how uncertainties in voltage and current measurements propagate into the calculated resistance.
