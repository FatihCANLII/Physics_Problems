# 4. Relative Uncertainty

We use **Relative Uncertainty** (often expressed as a percentage) to determine the actual interval or range of a measured value. In this problem, a car's speedometer reads:

$$v = 60 \text{ km/h with a } 5\% \text{ uncertainty}$$

In this file, we will calculate the absolute uncertainty and find the range of the car's actual speed in 3 simple steps.

---

## 1. Identify the Given Values

Let's break down the information provided:

* **Measured Value ($v$):** $60 \text{ km/h}$ (The speed shown on the dashboard)
* **Percentage Uncertainty:** $5\%$ (The relative error margin of the speedometer)

---

## 2. The Formulas to Use

First, we need to calculate the **Absolute Uncertainty ($\Delta v$)** from the percentage error:

> $$\Delta v = \text{Measured Value} \times \left( \frac{\text{Percentage Uncertainty}}{100} \right)$$

Once we find $\Delta v$, the **Actual Speed Range** is expressed by bounding the measurement between its minimum and maximum possible values:

> $$\text{Range} = v \pm \Delta v \implies [v - \Delta v, v + \Delta v]$$

---

## 3. Step-by-Step Solution

### **Step 1: Calculate the Absolute Uncertainty**
Multiply the measured speed by the percentage uncertainty to find the exact error in km/h:

$$\Delta v = 60 \times \frac{5}{100}$$
$$\Delta v = 60 \times 0.05 = 3 \text{ km/h}$$

*This tells us that the speedometer reading can be off by up to $3 \text{ km/h}$ above or below the actual speed.*

### **Step 2: Calculate the Minimum Speed**
Subtract the absolute uncertainty from the reading:

$$\text{Minimum Speed} = 60 - 3 = 57 \text{ km/h}$$

### **Step 3: Calculate the Maximum Speed**
Add the absolute uncertainty to the reading:

$$\text{Maximum Speed} = 60 + 3 = 63 \text{ km/h}$$

---

## Summary and Conclusion

The car's actual speed expressed in proper measurement notation is:

$$v = 60 \pm 3 \text{ km/h}$$

* **Actual Speed Range:** **$57 \text{ km/h}$ to $63 \text{ km/h}$**

> **Presentation Tip:** Explain to your audience that even though the speedometer displays a steady $60 \text{ km/h}$, the physical limitations and calibration of the device mean the car's true velocity safely falls anywhere within the $57$ to $63 \text{ km/h}$ window.
