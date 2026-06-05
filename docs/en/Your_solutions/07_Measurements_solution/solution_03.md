# 3. Propagation of Error III

In this problem, the resistance is calculated using Ohm’s Law. Since both the voltage and the current contain measurement uncertainties, the calculated resistance will also have an uncertainty.

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

## Step 2: Calculate the Relative Uncertainty

Since resistance is obtained by dividing two measured quantities, the relative uncertainties must be combined.

First, calculate the relative uncertainty of the voltage:

$$
\frac{0.2}{10.0} = 0.02
$$

Then, calculate the relative uncertainty of the current:

$$
\frac{0.05}{2.00} = 0.025
$$

Combining these uncertainties gives:

$$
\frac{\Delta R}{R} = 0.032
$$

This means the resistance has a relative uncertainty of:

$$
3.2\%
$$

---

## Step 3: Calculate the Absolute Uncertainty

To obtain the absolute uncertainty in resistance:

$$
\Delta R = R \times 0.032
$$

Substituting the value of the resistance:

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
R = (5.00 \pm 0.16)\Omega
$$

Therefore, the measured resistance is expected to be:

$$
4.84\Omega \leq R \leq 5.16\Omega
$$
