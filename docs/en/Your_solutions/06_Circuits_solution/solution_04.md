## 4. Mixed Circuit Solution

**Problem:** Calculate the equivalent resistance for the circuit shown in the figure. All resistors have a resistance of $10\,\Omega$.

**Step-by-Step Calculation:**

**1. Top Branch**
The top branch consists of two resistors in series.
* $R_{top} = 10\,\Omega + 10\,\Omega = 20\,\Omega$

**2. Bottom Branch**
The bottom branch has two resistors in parallel, which are in series with a single resistor.
* First, calculate the parallel pair: $R_{pair} = \left(\frac{1}{10} + \frac{1}{10}\right)^{-1} = 5\,\Omega$
* Add the series resistor in this branch: $R_{bottom} = 10\,\Omega + 5\,\Omega = 15\,\Omega$

**3. Combine the Parallel Branches**
Now we treat the top branch ($20\,\Omega$) and the bottom branch ($15\,\Omega$) as two parallel components.
* $R_{parallel\_section} = \left(\frac{1}{20} + \frac{1}{15}\right)^{-1}$
* Common denominator is 60: $\frac{3}{60} + \frac{4}{60} = \frac{7}{60}$
* $R_{parallel\_section} = \frac{60}{7}\,\Omega$

**4. Total Equivalent Resistance**
The entire parallel section is in series with the final resistor on the right side of the circuit.
* $R_{eq} = R_{parallel\_section} + 10\,\Omega$
* $R_{eq} = \frac{60}{7} + \frac{70}{7} = \frac{130}{7}\,\Omega$

**Final Answer:**
The equivalent resistance of the circuit is **$\frac{130}{7}\,\Omega$** (approximately $18.57\,\Omega$).
