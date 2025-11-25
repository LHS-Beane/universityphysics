📘 WEEK 1 — Units, Dimensions, & 1D Kinematics (with Calculus)

Sessions: Oct 21 & 23
Module Type: Full lesson for students who missed class

🎯 Learning Goals

By the end of Week 1, you will be able to:

Convert and analyze physical quantities using dimensional analysis

Interpret position, velocity, and acceleration graphs & functions

Use derivatives to compute velocity and acceleration

Use integrals to compute velocity and position

Solve constant and non-constant acceleration problems

Model free fall using calculus

Understand the foundation of Test 1

------------------------------------------------------------------------------------
📘 1. Units, Dimensions, and Dimensional Analysis
------------------------------------------------------------------------------------
1.1 SI Base Units
Quantity	Unit	Symbol
Length	meter	m
Mass	kilogram	kg
Time	second	s
Temperature	kelvin	K
Electric current	ampere	A
Derived Units

Examples:

Velocity: m/s

Acceleration: m/s²

Force: Newton (N = kg·m/s²)

Energy: Joule (J = N·m = kg·m²/s²)

1.2 Dimensions

Dimensions describe the type of physical quantity.

Example:

Velocity: 
[
𝐿
]
[
𝑇
−
1
]
[L][T
−1
]

Force: 
[
𝑀
]
[
𝐿
]
[
𝑇
−
2
]
[M][L][T
−2
]

Why it matters

Dimensional analysis can:

Check if an equation is valid

Help derive physical relationships

Example – Dimensional Check

Is 
𝑣
=
3
𝑡
+
7
𝑥
v=3t+7x physically valid?

Left: 
𝑣
v is 
[
𝐿
/
𝑇
]
[L/T]
Right terms:

3
𝑡
→
[
𝑇
]
3t→[T]

7
𝑥
→
[
𝐿
]
7x→[L]

These cannot be added → INVALID

1.3 Unit Conversions

Use the factor-label method.

Example

Convert 60 mph to m/s:

60
 mi/hr
⋅
1609
 m
1
 mi
⋅
1
 hr
3600
 s
60 mi/hr⋅
1 mi
1609 m
	​

⋅
3600 s
1 hr
	​


= 26.8 m/s

------------------------------------------------------------------------------------
📘 2. Position, Velocity, and Acceleration
------------------------------------------------------------------------------------

Before calculus, students memorize:

𝑣
=
𝑑
𝑥
𝑑
𝑡
,
𝑎
=
𝑑
𝑣
𝑑
𝑡
v=
dt
dx
	​

,a=
dt
dv
	​


But in this course, you learn why these definitions exist.

2.1 Position Function

Position 
𝑥
(
𝑡
)
x(t) tells you where an object is at any time.

Example function:
𝑥
(
𝑡
)
=
𝑡
3
−
4
𝑡
+
2
x(t)=t
3
−4t+2

Its graph would curve (since it’s cubic).

2.2 Velocity

Velocity is the rate of change of position:

𝑣
(
𝑡
)
=
𝑑
𝑥
𝑑
𝑡
v(t)=
dt
dx
	​


Using the example above:

𝑣
(
𝑡
)
=
3
𝑡
2
−
4
v(t)=3t
2
−4
Graph Interpretation

Where 
𝑣
>
0
v>0, motion is forward

Where 
𝑣
<
0
v<0, motion is backward

Where 
𝑣
=
0
v=0, turning points occur

2.3 Acceleration

Acceleration is the derivative of velocity:

𝑎
(
𝑡
)
=
𝑑
𝑣
𝑑
𝑡
a(t)=
dt
dv
	​


Example:

𝑎
(
𝑡
)
=
6
𝑡
a(t)=6t

Meaning:

Positive values → speeding up

Negative values → slowing down

------------------------------------------------------------------------------------
📘 3. Derivatives in Kinematics
------------------------------------------------------------------------------------

Students must learn:

𝑣
(
𝑡
)
=
𝑑
𝑥
𝑑
𝑡
𝑎
(
𝑡
)
=
𝑑
𝑣
𝑑
𝑡
v(t)=
dt
dx
	​

a(t)=
dt
dv
	​

Example 1 – Derivative Practice

Let:

𝑥
(
𝑡
)
=
5
𝑡
2
−
3
𝑡
+
8
x(t)=5t
2
−3t+8

Then:

𝑣
(
𝑡
)
=
10
𝑡
−
3
v(t)=10t−3
𝑎
(
𝑡
)
=
10
a(t)=10

Interpretation:

Constant positive acceleration

Linear velocity

Quadratic position

------------------------------------------------------------------------------------
📘 4. Integration in Kinematics
------------------------------------------------------------------------------------

If given acceleration:

𝑣
(
𝑡
)
=
∫
𝑎
(
𝑡
)
 
𝑑
𝑡
v(t)=∫a(t)dt

If given velocity:

𝑥
(
𝑡
)
=
∫
𝑣
(
𝑡
)
 
𝑑
𝑡
x(t)=∫v(t)dt
4.1 Constant Acceleration

If 
𝑎
a is constant:

𝑣
(
𝑡
)
=
𝑣
0
+
𝑎
𝑡
v(t)=v
0
	​

+at
𝑥
(
𝑡
)
=
𝑥
0
+
𝑣
0
𝑡
+
1
2
𝑎
𝑡
2
x(t)=x
0
	​

+v
0
	​

t+
2
1
	​

at
2

These are the standard kinematic equations.

4.2 Non-Constant Acceleration
Example
𝑎
(
𝑡
)
=
4
𝑡
a(t)=4t

Then:

𝑣
(
𝑡
)
=
∫
4
𝑡
 
𝑑
𝑡
=
2
𝑡
2
+
𝐶
v(t)=∫4tdt=2t
2
+C

Use initial conditions to find 
𝐶
C.

4.3 Free Fall

Take downward as positive:

𝑎
=
𝑔
=
9.8
 
m/s
2
a=g=9.8 m/s
2

Velocity:

𝑣
(
𝑡
)
=
𝑔
𝑡
+
𝑣
0
v(t)=gt+v
0
	​


Position:

𝑥
(
𝑡
)
=
𝑥
0
+
𝑣
0
𝑡
+
1
2
𝑔
𝑡
2
x(t)=x
0
	​

+v
0
	​

t+
2
1
	​

gt
2

If dropped (released from rest):

𝑣
0
=
0
v
0
	​

=0

𝑥
0
x
0
	​

 = starting height

------------------------------------------------------------------------------------
📘 5. Graph Interpretation (Critical for Test 1)
------------------------------------------------------------------------------------

Students must interpret position/velocity/acceleration graphs.

5.1 Position → Velocity

Velocity is the slope of a position graph.

5.2 Velocity → Acceleration

Acceleration is the slope of a velocity graph.

5.3 Velocity → Displacement

Area under the velocity curve = displacement.

------------------------------------------------------------------------------------
📘 6. Worked Examples
------------------------------------------------------------------------------------
Example 1 — From Position to Velocity & Acceleration
𝑥
(
𝑡
)
=
4
𝑡
3
−
2
𝑡
x(t)=4t
3
−2t

Find velocity and acceleration.

𝑣
(
𝑡
)
=
12
𝑡
2
−
2
v(t)=12t
2
−2
𝑎
(
𝑡
)
=
24
𝑡
a(t)=24t
Example 2 — Dropped Object

A ball is dropped from rest at a height of 20 m.

Find:

Velocity after 2 seconds

Position after 2 seconds

Solution:

𝑣
(
𝑡
)
=
𝑔
𝑡
=
9.8
(
2
)
=
19.6
 m/s
v(t)=gt=9.8(2)=19.6 m/s
𝑥
(
𝑡
)
=
20
−
1
2
(
9.8
)
(
2
2
)
x(t)=20−
2
1
	​

(9.8)(2
2
)
𝑥
(
𝑡
)
=
20
−
19.6
=
0.4
 m
x(t)=20−19.6=0.4 m
Example 3 — Integrating Non-Constant Acceleration
𝑎
(
𝑡
)
=
6
𝑡
a(t)=6t
𝑣
(
0
)
=
3
v(0)=3

Find velocity and position.

Velocity:

𝑣
(
𝑡
)
=
∫
6
𝑡
 
𝑑
𝑡
=
3
𝑡
2
+
𝐶
=
3
𝑡
2
+
3
v(t)=∫6tdt=3t
2
+C=3t
2
+3

Position:

𝑥
(
𝑡
)
=
∫
(
3
𝑡
2
+
3
)
𝑑
𝑡
x(t)=∫(3t
2
+3)dt
𝑥
(
𝑡
)
=
𝑡
3
+
3
𝑡
+
𝐶
2
x(t)=t
3
+3t+C
2
	​


If 
𝑥
(
0
)
=
0
x(0)=0, then 
𝐶
2
=
0
C
2
	​

=0.

------------------------------------------------------------------------------------
📘 7. Practice Problems (Students Should Try These)
------------------------------------------------------------------------------------
1.

Given 
𝑥
(
𝑡
)
=
2
𝑡
3
−
5
𝑡
2
+
7
x(t)=2t
3
−5t
2
+7, find:

𝑣
(
𝑡
)
v(t)

𝑎
(
𝑡
)
a(t)

2.

A car starts from rest and accelerates at 4 m/s² for 5 seconds.
Find the distance traveled.

3.

A ball is thrown upward at 12 m/s.
Find the max height.

4.

Convert 45 mph to m/s.

5.

Velocity is 
𝑣
(
𝑡
)
=
6
𝑡
v(t)=6t. If 
𝑥
(
0
)
=
0
x(0)=0, find 
𝑥
(
𝑡
)
x(t).

------------------------------------------------------------------------------------
📘 8. Mini Quiz (Auto-Check Friendly)
------------------------------------------------------------------------------------
1. If velocity is the derivative of position, what is acceleration?

✔ Derivative of velocity

2. True or False: acceleration can change even if velocity is zero.

✔ True (turning point)

3. A ball dropped has initial velocity:

✔ 0 m/s

4. If 
𝑎
(
𝑡
)
=
10
a(t)=10, what kind of function is 
𝑣
(
𝑡
)
v(t)?

✔ Linear

------------------------------------------------------------------------------------
📘 9. Summary Sheet (What You Must Know for Test 1)
------------------------------------------------------------------------------------
Formulas to know:
𝑣
(
𝑡
)
=
𝑑
𝑥
𝑑
𝑡
v(t)=
dt
dx
	​

𝑎
(
𝑡
)
=
𝑑
𝑣
𝑑
𝑡
a(t)=
dt
dv
	​

𝑣
(
𝑡
)
=
𝑣
0
+
𝑎
𝑡
v(t)=v
0
	​

+at
𝑥
(
𝑡
)
=
𝑥
0
+
𝑣
0
𝑡
+
1
2
𝑎
𝑡
2
x(t)=x
0
	​

+v
0
	​

t+
2
1
	​

at
2
Concepts to know:

Slope interpretation

Area under curve interpretation

Free fall modeling

Unit conversions

Dimensional analysis

This closes Week 1.
