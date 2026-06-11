# 3. Propagation of Error III

In this problem, the resistance is calculated using Ohm’s Law. Since both the voltage and current contain measurement uncertainties, the calculated resistance will also have an uncertainty.

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

## Step 2: Use the Propagation of Uncertainty Formula

Since resistance depends on both voltage and current, uncertainty in both quantities affects the final result.

For:

$$
R = \frac{V}{I}
$$

the uncertainty in resistance is calculated as:

First part:

$$
\frac{1}{2.00}\times0.2 = 0.10
$$

Second part:

$$
\frac{10.0}{(2.00)^2}\times0.05 = 0.125
$$

Then combine them:

$$
\Delta R = \sqrt{(0.10)^2 + (0.125)^2}
$$

This formula shows how the uncertainties in voltage and current propagate into the resistance.

---

## Step 3: Substitute the Values

The given values are:

$$
V = 10.0
$$

$$
I = 2.00
$$

$$
\Delta V = 0.2
$$

$$
\Delta I = 0.05
$$

Substitute these values step by step.

Now calculate each part separately:

$$
\frac{1}{2.00}\times0.2 = 0.10
$$

$$
\frac{10.0}{(2.00)^2}\times0.05 = 0.125
$$

So:

$$
\Delta R = \sqrt{(0.10)^2 + (0.125)^2}
$$

$$
\Delta R = \sqrt{0.01 + 0.015625}
$$

$$
\Delta R = \sqrt{0.025625}
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
R = (5.00 \pm 0.16)\Omega
$$

Therefore, the measured resistance is expected to lie within the interval:

$$
4.84\Omega \leq R \leq 5.16\Omega
$$

This result shows how uncertainties in voltage and current measurements affect the calculated resistance.
