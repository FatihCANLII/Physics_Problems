# 4. Mixed Circuit

All resistors have resistance:

\[
R = 10\ \Omega
\]

The circuit can be separated into two main branches between the left node and the middle-right node.

## Top Branch

The top branch has two resistors in series:

\[
R_{\text{top}} = 10 + 10 = 20\ \Omega
\]

## Bottom Branch

The bottom branch first has one resistor in series with two parallel resistors.

The two parallel resistors are:

\[
R_{\parallel} = \frac{10 \times 10}{10 + 10}
\]

\[
R_{\parallel} = 5\ \Omega
\]

So the bottom branch is:

\[
R_{\text{bottom}} = 10 + 5 = 15\ \Omega
\]

## Combining the Two Branches

The top and bottom branches are in parallel:

\[
R_{\text{middle}} =
\frac{R_{\text{top}}R_{\text{bottom}}}
{R_{\text{top}} + R_{\text{bottom}}}
\]

\[
R_{\text{middle}} =
\frac{20 \times 15}{20 + 15}
=
\frac{300}{35}
=
\frac{60}{7}\ \Omega
\]

## Final Series Resistor

There is one more \(10\ \Omega\) resistor in series on the right side:

\[
R_{\text{eq}} =
\frac{60}{7} + 10
\]

\[
R_{\text{eq}} =
\frac{60}{7} + \frac{70}{7}
=
\frac{130}{7}\ \Omega
\]

\[
\boxed{R_{\text{eq}} = \frac{130}{7}\ \Omega \approx 18.57\ \Omega}
\]

Final answer:

\[
\boxed{18.57\ \Omega}
\]
