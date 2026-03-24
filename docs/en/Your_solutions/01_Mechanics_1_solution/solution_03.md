We are given the position vectors:

A(t) = (2 + t, 8 - 3t)
B(t) = (2t - 1, 2t + 2)

We want to check whether Alice and Bob collide, meaning they are at the same position at the same time.

---

## Step 1: Set the coordinates equal

For a collision, both x- and y-coordinates must match at the same time t.

### x-coordinates:
2 + t = 2t - 1

Solve:
2 + t = 2t - 1
2 = t - 1
t = 3

### y-coordinates:
8 - 3t = 2t + 2

Solve:
8 - 3t = 2t + 2
6 = 5t
t = 6/5

---

## Step 2: Compare the times

From the x-coordinate equation:
t = 3

From the y-coordinate equation:
t = 6/5

Since these are **not equal**, there is **no single time t** at which both coordinates are equal.

So, **Alice and Bob do not collide**.

---

## Step 3: Find the distance between them

The displacement from Bob to Alice is:

D(t) = A(t) - B(t)

= (2 + t - (2t - 1), 8 - 3t - (2t + 2))
= (3 - t, 6 - 5t)

So the distance is:

d(t) = sqrt((3 - t)^2 + (6 - 5t)^2)

To minimize the distance, minimize the squared distance:

d^2(t) = (3 - t)^2 + (6 - 5t)^2

---

## Step 4: Expand d²(t)

d^2(t) = (3 - t)^2 + (6 - 5t)^2
       = (9 - 6t + t^2) + (36 - 60t + 25t^2)
       = 45 - 66t + 26t^2

So:

d^2(t) = 26t^2 - 66t + 45

---

## Step 5: Minimize d²(t)

Differentiate:

d/dt [d^2(t)] = 52t - 66

Set equal to zero:

52t - 66 = 0
52t = 66
t = 66/52 = 33/26

---

## Step 6: Find the minimum distance

Substitute t = 33/26 into:

d^2(t) = 26t^2 - 66t + 45

d^2(33/26) = 26(33/26)^2 - 66(33/26) + 45
           = 1089/26 - 1089/13 + 45
           = 1089/26 - 2178/26 + 1170/26
           = 81/26

Therefore:

d_min = sqrt(81/26)
      = 9/sqrt(26)

Rationalized form:

d_min = 9sqrt(26)/26

---

## Step 7: Find their positions at that time

At t = 33/26:

### Alice:
A(33/26) = (2 + 33/26, 8 - 3(33/26))
         = (85/26, 109/26)

### Bob:
B(33/26) = (2(33/26) - 1, 2(33/26) + 2)
         = (20/13, 59/13)

These are different points, confirming again that they do not collide.

---

## Final Answer

The paths do **not intersect at the same time**, so Alice and Bob do **not collide**.

The **minimum distance** between them occurs at:

t = 33/26

and the minimum distance is:

d_min = 9/sqrt(26) = 9sqrt(26)/26
