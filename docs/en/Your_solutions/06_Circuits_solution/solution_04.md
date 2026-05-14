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

$$ R_{\text{middle}} = \frac{20 \times 15}{20 + 15} $$

$$ R_{\text{middle}} = \frac{300}{35} = \frac{60}{7}\ \Omega $$

## Final Series Resistor

There is one additional resistor of \(10\ \Omega\) in series on the right side.

$$ R_{\text{eq}} = \frac{60}{7} + 10 $$

$$ 10 = \frac{70}{7} $$

$$ R_{\text{eq}} = \frac{60}{7} + \frac{70}{7} = \frac{130}{7}\ \Omega $$

$$ R_{\text{eq}} \approx 18.57\ \Omega $$

## Final Answer

$$ \boxed{R_{\text{eq}} \approx 18.57\ \Omega} $$
