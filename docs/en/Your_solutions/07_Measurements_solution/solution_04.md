# 4. Relative Uncertainty

In this example, we examine how uncertainty affects a speed measurement. Even though a speedometer may display a single value, the true speed can actually be slightly higher or lower because every measuring device has some margin of error.

The speedometer reading is:

$$
v = 60 \text{ km/h}
$$

The uncertainty of the device is:

$$
5\%
$$

Our goal is to determine the possible range of the car’s real speed.

---

## Step 1: Calculate the Absolute Uncertainty

A percentage uncertainty must first be converted into an absolute uncertainty value.

We use the formula:

$$
\Delta v = v \times \frac{\text{percentage uncertainty}}{100}
$$

Substituting the known values:

$$
\Delta v = 60 \times \frac{5}{100}
$$

$$
\Delta v = 60 \times 0.05
$$

$$
\Delta v = 3 \text{ km/h}
$$

This means the speedometer can differ from the actual speed by up to:

$$
\pm 3 \text{ km/h}
$$

---

## Step 2: Determine the Minimum Possible Speed

To find the lowest possible speed, subtract the uncertainty from the measured value:

$$
v_{\text{min}} = 60 - 3
$$

$$
v_{\text{min}} = 57 \text{ km/h}
$$

---

## Step 3: Determine the Maximum Possible Speed

To find the highest possible speed, add the uncertainty to the measured value:

$$
v_{\text{max}} = 60 + 3
$$

$$
v_{\text{max}} = 63 \text{ km/h}
$$

---

## Final Result

The actual speed of the car is expected to lie within the interval:

$$
57 \text{ km/h} \leq v \leq 63 \text{ km/h}
$$

Using standard uncertainty notation, the measurement can also be written as:

$$
v = (60 \pm 3)\text{ km/h}
$$
