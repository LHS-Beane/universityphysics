# 📘 WEEK 1 — Units, Dimensions, & 1D Kinematics (with Calculus)

**Sessions:** Oct 21 & 23  
**Module Type:** Full lesson for students who missed class

---

# 🎯 Learning Goals

By the end of Week 1, you will be able to:

- Convert and analyze physical quantities using dimensional analysis
- Interpret position, velocity, and acceleration graphs & functions
- Use derivatives to compute velocity and acceleration
- Use integrals to compute velocity and position
- Solve constant and non-constant acceleration problems
- Model free fall using calculus
- Understand the foundation of Test 1

---

# 📘 1. Units, Dimensions, and Dimensional Analysis

## 1.1 SI Base Units

| Quantity | Unit | Symbol |
|---------|------|--------|
| Length | meter | m |
| Mass | kilogram | kg |
| Time | second | s |
| Temperature | kelvin | K |
| Electric current | ampere | A |

---

## 1.2 Derived Units

Examples:

- Velocity: m/s  
- Acceleration: m/s²  
- Force: Newton (N = kg·m/s²)  
- Energy: Joule (J = N·m = kg·m²/s²)

---

## 1.3 Dimensions

Dimensions describe the *type* of physical quantity.

Examples:

\[
\text{Velocity}: [L][T^{-1}]
\]

\[
\text{Force}: [M][L][T^{-2}]
\]

### Why it matters

Dimensional analysis can:

- Check if an equation is valid  
- Help derive relationships  

### Example – Dimensional Check

Is the equation

\[
v = 3t + 7x
\]

valid?

Left side:

\[
[v] = [L/T]
\]

Right side:

- \(3t \rightarrow [T]\)  
- \(7x \rightarrow [L]\)

These units cannot be added.  
➡️ **Invalid equation**

---

## 1.4 Unit Conversions

Use the factor-label method.

### Example: Convert 60 mph to m/s

\[
60 \frac{\text{mi}}{\text{hr}}
\cdot
\frac{1609\ \text{m}}{1\ \text{mi}}
\cdot
\frac{1\ \text{hr}}{3600\ \text{s}}
=
26.8\ \text{m/s}
\]

---

# 📘 2. Position, Velocity, and Acceleration

Before calculus, students memorize:

\[
v = \frac{dx}{dt}, \qquad a = \frac{dv}{dt}
\]

In this course, you learn **why** these definitions matter.

---

## 2.1 Position Function

Position:

\[
x(t)
\]

Example:

\[
x(t) = t^3 - 4t + 2
\]

A cubic function curves up and down depending on time.

---

## 2.2 Velocity

Velocity is the derivative of position:

\[
v(t) = \frac{dx}{dt}
\]

Using the example:

\[
v(t) = 3t^2 - 4
\]

Interpretation:

- \(v > 0\) → moving forward  
- \(v < 0\) → moving backward  
- \(v = 0\) → turning point  

---

## 2.3 Acceleration

Acceleration is the derivative of velocity:

\[
a(t) = \frac{dv}{dt}
\]

Example:

\[
a(t) = 6t
\]

Meaning:

- Positive → speeding up  
- Negative → slowing down  

---

# 📘 3. Derivatives in Kinematics

Students must learn:

\[
v(t) = \frac{dx}{dt}
\]

\[
a(t) = \frac{dv}{dt}
\]

### Example 1 — Derivative Practice

Let:

\[
x(t) = 5t^2 - 3t + 8
\]

Then:

\[
v(t) = 10t - 3
\]

\[
a(t) = 10
\]

Interpretation:

- Constant positive acceleration  
- Linear velocity  
- Quadratic position  

---

# 📘 4. Integration in Kinematics

If acceleration is known:

\[
v(t) = \int a(t)\,dt
\]

If velocity is known:

\[
x(t) = \int v(t)\,dt
\]

---

## 4.1 Constant Acceleration

When \(a\) is constant:

\[
v(t) = v_0 + at
\]

\[
x(t)=x_0 + v_0 t + \frac{1}{2}at^2
\]

These are the standard kinematics equations.

---

## 4.2 Non-Constant Acceleration Example

\[
a(t)=4t
\]

Then:

\[
v(t) = \int 4t\,dt = 2t^2 + C
\]

Use initial conditions to find \(C\).

---

## 4.3 Free-Fall Motion

Take downward as positive:

\[
a=g=9.8\ \text{m/s}^2
\]

Velocity:

\[
v(t)=gt + v_0
\]

Position:

\[
x(t)=x_0 + v_0 t + \frac{1}{2}gt^2
\]

If dropped:  
- \(v_0 = 0\)  
- \(x_0\) = starting height  

---

# 📘 5. Graph Interpretation (Critical for Test 1)

### Position → Velocity  
Velocity is the **slope** of the position graph.

### Velocity → Acceleration  
Acceleration is the **slope** of the velocity graph.

### Velocity → Displacement  
Displacement equals the **area under the velocity curve**.

---

# 📘 6. Worked Examples

### Example 1 — From \(x(t)\) to \(v(t)\) and \(a(t)\)

\[
x(t)=4t^3 - 2t
\]

\[
v(t)=12t^2 - 2
\]

\[
a(t)=24t
\]

---

### Example 2 — Dropped Object

A ball is dropped from rest at a height of 20 m.

**Velocity after 2 seconds:**

\[
v = gt = 9.8(2)=19.6\ \text{m/s}
\]

**Position after 2 seconds:**

\[
x = 20 - \frac{1}{2}(9.8)(2^2)=20 - 19.6 = 0.4\ \text{m}
\]

---

### Example 3 — Non-Constant Acceleration

\[
a(t)=6t,\quad v(0)=3
\]

Velocity:

\[
v(t)=3t^2 + 3
\]

Position:

\[
x(t)=t^3 + 3t
\]

---

# 📘 7. Practice Problems

1. Given  
   \[
   x(t)=2t^3 - 5t^2 + 7
   \]  
   find \(v(t)\) and \(a(t)\).

2. A car starts from rest and accelerates at 4 m/s² for 5 seconds.  
   Find the distance traveled.

3. A ball is thrown upward at 12 m/s.  
   Find the maximum height.

4. Convert 45 mph to m/s.

5. If \(v(t)=6t\) and \(x(0)=0\), find \(x(t)\).

---

# 📘 8. Mini-Quiz (Self-Check)

1. If velocity is the derivative of position, what is acceleration?  
   ✔ Derivative of velocity  

2. True or False: acceleration can change even when velocity is zero.  
   ✔ True  

3. A ball dropped has initial velocity:  
   ✔ 0 m/s  

4. If \(a(t)=10\), what kind of function is \(v(t)\)?  
   ✔ Linear  

---

# 📘 9. Summary Sheet (What You Must Know for Test 1)

### Must-Know Formulas:

\[
v(t) = \frac{dx}{dt}
\]

\[
a(t) = \frac{dv}{dt}
\]

\[
v(t)=v_0 + at
\]

\[
x(t)=x_0 + v_0 t + \frac{1}{2}at^2
\]

### Must-Know Concepts:

- Slope interpretation (graphs)  
- Area under velocity curve  
- Free-fall modeling  
- Unit conversions  
- Dimensional analysis  

---

# 🎉 Week 1 Complete!

