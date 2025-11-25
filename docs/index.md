 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/docs/index.md b/docs/index.md
index 155b423761871dd0d085f281a1dcc202ea747fb8..0ce3ac39a97cdf106746c4a111c3e69e15beeb2d 100644
--- a/docs/index.md
+++ b/docs/index.md
@@ -1,10 +1,41 @@
-# Welcome to Physics 201
+# Physics 201: University Physics I
 
-## Mathematics Test
-Testing the integral:
+Welcome to the interactive course hub for a calculus-based introduction to mechanics, waves, and thermodynamics. Use the navigation tabs to explore the syllabus, weekly modules, and study resources.

+## Course Snapshot
 
+- **Instructor:** TBD · **Credits:** 3 · **Format:** 3 hours lecture 
+- **Prerequisite:** Calculus I (differentiation and basic integration)
+- **Course Goals:** Build intuition for motion, forces, energy, momentum, and the foundations of waves. Practice modeling real systems with calculus and interpreting experimental results.
+
+## What you will learn
+
+1. Translate physical scenarios into mathematical models using vectors, derivatives, and integrals.
+2. Apply Newton's laws, conservation principles, and work–energy methods to solve multi-step problems.
+3. Analyze oscillations and wave phenomena in mechanical and acoustic systems.
+4. Communicate solutions and lab findings using clear reasoning, units, and significant figures.
+
+## Quick checks
+
+Use these expandable questions to self-test as you go through the course.
+
+??? question "Why do we write forces as vectors?"
+    Forces have both magnitude and direction; representing them as vectors lets us add components, apply Newton's laws in each dimension, and use tools like dot products when computing work.
+
+??? example "Where does calculus appear in kinematics?"
+    Position $\vec{r}(t)$, velocity $\vec{v}(t)$, and acceleration $\vec{a}(t)$ are linked by derivatives:
+    $$\vec{v}(t) = \frac{d\vec{r}}{dt}, \qquad \vec{a}(t) = \frac{d\vec{v}}{dt}.$$
+    Integrals reverse the process to find displacement or velocity changes from acceleration data.
+
+## Weekly rhythm
+
+- **Lecture (3×/week):** Active problem solving with clicker-style questions and derivations.
+- **Lab (1×/week):** Hands-on experiments using motion sensors, force probes, and data analysis in spreadsheets or Python.
+- **Recitation/office hours:** Additional guided practice and conceptual troubleshooting.
+
+## Getting started
+
+- Review vector algebra and one-dimensional derivatives before Week 1.
+- Set up a problem-solving notebook (paper or digital) to track solved examples and open questions.
+- Bookmark the course formula sheet and simulation links on the Resources page.
 
EOF
)
