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

We use this formula because Ohm's Law defines resistance as the ratio of voltage to current.

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

Since resistance is obtained by dividing two measured quantities, the uncertainties of both measurements contribute to the final uncertainty.

For division, uncertainty propagation is performed using relative uncertainties.

First, calculate the relative uncertainty of the voltage:

$$
\frac{\Delta V}{V}
=
\frac{0.2}{10.0}
=
0.02
$$

Then, calculate the relative uncertainty of the current:

$$
\frac{\Delta I}{I}
=
\frac{0.05}{2.00}
=
0.025
$$

The relative uncertainty of the resistance is obtained by combining these contributions:

$$
\frac{\Delta R}{R}
=
0.032
$$

We calculate the relative uncertainty first because uncertainty formulas for multiplication and division are based on relative uncertainties rather than absolute uncertainties.

This means the resistance has a relative uncertainty of:

$$
3.2\%
$$

---

## Step 3: Calculate the Absolute Uncertainty

Now we convert the relative uncertainty into an absolute uncertainty.

We use:

$$
\Delta R = R \times \frac{\Delta R}{R}
$$

We use this formula because the relative uncertainty must be converted into the same unit as the resistance, which is ohms.

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
R = (5.00 \pm 0.16)\Omega
$$

Therefore, the measured resistance is expected to be:

$$
4.84\Omega \leq R \leq 5.16\Omega
$$

This example demonstrates how uncertainties from multiple measurements propagate into a calculated quantity and affect the final result.
