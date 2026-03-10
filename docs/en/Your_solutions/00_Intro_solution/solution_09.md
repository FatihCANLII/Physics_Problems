## 9. Optimization Problem

A rectangle is under the curve

$$
y = 3 - x^2
$$

in the **first quadrant**. We want to find the dimensions of the rectangle with the **maximum area**.

---

## Step 1: Describe the Rectangle

Let the upper-right corner of the rectangle be at the point \((x, y)\) on the curve.

Since the point lies on the curve:

$$
y = 3 - x^2
$$

Because the rectangle is in the first quadrant and lies under the curve:

- its **width** is \(x\)
- its **height** is \(y = 3 - x^2\)

---

## Step 2: Write the Area Function

The area of the rectangle is:

$$
A = \text{width} \times \text{height}
$$

So,

$$
A(x) = x(3 - x^2)
$$

Simplify:

$$
A(x) = 3x - x^3
$$

---

## Step 3: Differentiate the Area Function

To find the maximum area, differentiate \(A(x)\):

$$
A'(x) = \frac{d}{dx}(3x - x^3)
$$

$$
A'(x) = 3 - 3x^2
$$

---

## Step 4: Find Critical Points

Set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

Divide both sides by \(3\):

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

Since we are in the **first quadrant**, we take the positive value:

$$
x = 1
$$

---

## Step 5: Find the Corresponding Height

Substitute \(x = 1\) into the curve equation:

$$
y = 3 - x^2
$$

$$
y = 3 - 1^2
$$

$$
y = 3 - 1
$$

$$
y = 2
$$

---

## Step 6: Confirm It Is a Maximum

The second derivative is:

$$
A''(x) = -6x
$$

At \(x = 1\):

$$
A''(1) = -6
$$

Since \(A''(1) < 0\), the area is maximized at \(x = 1\).

---

## Final Answer

The rectangle with the maximum area has:

- **width** \(= 1\)
- **height** \(= 2\)

So the dimensions are:

$$
1 \times 2
$$
