# 4. Relative Uncertainty

We use **Relative Uncertainty** (often expressed as a percentage) to determine the actual interval or range of a measured value. This helps us understand how reliable a device's reading really is.

In this problem, a car's speedometer provides the following reading:
$$v = 60 \text{ km/h with a } 5\% \text{ uncertainty}$$

Here is the step-by-step calculation to find the range of the car's actual speed.

---

## 1. Identify the Given Values

Before diving into the math, let's clearly define our known values:

* **Measured Value ($v$):** 60 km/h (The speed displayed on the dashboard)
* **Percentage Uncertainty:** 5% (The relative margin of error for this speedometer)

---

## 2. The Formulas to Use

To find the true speed range, we must complete two main steps:

1. **Convert percentage uncertainty into Absolute Uncertainty ($\Delta v$):**
   $$\Delta v = v \times \left( \frac{\text{Percentage Uncertainty}}{100} \right)$$

2. **Establish the Actual Speed Range:**
   $$\text{Range} = v \pm \Delta v \implies [v - \Delta v, \quad v + \Delta v]$$

---

## 3. Step-by-Step Solution

### **Step 1: Calculate the Absolute Uncertainty**
We multiply the reading by the percentage error to see how many km/h the speedometer can deviate:

$$\Delta v = 60 \times \frac{5}{100}$$
$$\Delta v = 60 \times 0.05 = 3 \text{ km/h}$$

*This result means the speedometer's reading can be off by up to 3 km/h either above or below the real speed.*

### **Step 2: Calculate the Minimum Possible Speed**
Subtract the absolute uncertainty from the speedometer reading:

$$\text{Minimum Speed} = v - \Delta v$$
$$\text{Minimum Speed} = 60 - 3 = 57 \text{ km/h}$$

### **Step 3: Calculate the Maximum Possible Speed**
Add the absolute uncertainty to the speedometer reading:

$$\text{Maximum Speed} = v + \Delta v$$
$$\text{Maximum Speed} = 60 + 3 = 63 \text{ km/h}$$

---

## Summary and Conclusion

When factoring in the device's uncertainty, the standard physics notation for this measurement is:

$$v = 60 \pm 3 \text{ km/h}$$

* **Actual Speed Range:** **57 km/h to 63 km/h**

> **Presentation Tip:** Remind your audience that even though the driver sees a steady 60 km/h on the dashboard, the actual physical speed of the vehicle safely fluctuates anywhere between 57 km/h and 63 km/h due to the 5% tolerance of the speedometer.
