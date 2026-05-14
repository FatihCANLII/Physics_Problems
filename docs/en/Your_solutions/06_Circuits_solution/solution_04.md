# 4. Mixed Circuit

All resistors have resistance:

$$
R = 10\ \Omega
$$

The circuit can be separated into two main branches between the left node and the middle-right node.

## Top Branch

The top branch has two resistors in series:

$$
R_{\text{top}} = 10 + 10 = 20\ \Omega
$$

## Bottom Branch

The bottom branch has one resistor in series with two parallel resistors.

First, calculate the two parallel resistors:

$$
R_{\parallel} = \frac{10 \times 10}{10 + 10}
$$

$$
R_{\parallel} = \frac{100}{20} = 5\ \Omega
$$

Now add the series resistor in the bottom branch:

$$
R_{\text{bottom}} = 10 + 5 = 15\ \Omega
$$

## Combining the Two Branches

The top and bottom branches are connected in parallel.

Using the parallel resistance formula:

$$
R_{\text{middle}} =
\frac{R_1 R_2}{R_1 + R_2}
$$

Substitute the values:

$$
R_{\text{middle}} =
\frac{20 \times 15}{20 + 15}
$$

$$
R_{\text{middle}} =
\frac{300}{35}
=
\frac{60}{7}\ \Omega
$$

---

## Final Series Resistor

There is one additional \(10\ \Omega\) resistor in series on the right side.

So the total equivalent resistance becomes:

$$
R_{\text{eq}} =
\frac{60}{7} + 10
$$

Convert \(10\) into sevenths:

$$
10 = \frac{70}{7}
$$

Now add the fractions:

$$
R_{\text{eq}} =
\frac{60}{7} + \frac{70}{7}
=
\frac{130}{7}\ \Omega
$$

Decimal form:

$$
R_{\text{eq}} \approx 18.57\ \Omega
$$

---

## Final Answer

$$
\boxed{R_{\text{eq}} \approx 18.57\ \Omega}
$$
