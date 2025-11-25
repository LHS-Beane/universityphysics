diff --git a/docs/modules.md b/docs/modules.md
new file mode 100644
index 0000000000000000000000000000000000000000..080c1a6c35b38a35244bd233ae6a6f86aa5887e8
--- /dev/null
+++ b/docs/modules.md
@@ -0,0 +1,89 @@
+# Weekly Modules
+
+Use this week-by-week outline to keep track of readings, labs, and key practice goals. Each module pairs lecture content with lab investigations and quick diagnostic questions.
+
+## Week 1: Motion in one dimension
+
+- **Focus:** Position, velocity, acceleration, and graphical reasoning.
+- **Reading:** Kinematics chapter intro; derivatives and units review.
+- **Practice targets:**
+  - Sketch motion diagrams and $x(t)$, $v(t)$, $a(t)$ graphs.
+  - Integrate acceleration data to recover velocity.
+- **Lab:** Motion sensor walk to connect graphs with movement.
+
+??? question "Checkpoint: What does slope represent on an $x(t)$ graph?"
+    The slope is the instantaneous velocity: $v = \frac{dx}{dt}$. A straight-line segment means constant velocity; curved segments indicate acceleration.
+
+## Week 2–3: Forces and Newton's laws
+
+- **Focus:** Free-body diagrams, Newton's three laws, friction, tension, and normal forces.
+- **Reading:** Forces and dynamics chapters; vector decomposition refresher.
+- **Practice targets:**
+  - Draw and decompose forces along chosen axes.
+  - Relate net force to acceleration with $\vec{F}_{\text{net}} = m\vec{a}$.
+- **Lab:** Atwood machine and friction cart experiments.
+
+??? tip "Free-body diagram checklist"
+    - Isolate the object; replace contacts with forces.
+    - Include gravity, normal, tension, friction, spring forces where applicable.
+    - Choose axes aligned with motion or constraints to simplify components.
+
+## Week 4–5: Work, energy, and conservation
+
+- **Focus:** Work-energy theorem, potential energy graphs, conservative vs. nonconservative forces.
+- **Reading:** Energy and work chapters; connection to calculus via line integrals.
+- **Practice targets:**
+  - Calculate work from force–displacement data: $W = \int \vec{F}\cdot d\vec{r}$.
+  - Use energy bar charts to track transfers and transformations.
+- **Lab:** Spring constant measurement and energy conservation with carts.
+
+??? example "Interpreting potential energy plots"
+    Turning points occur where $U(x)$ is at a local maximum or equals total mechanical energy $E$. The force relates to slope: $F_x = -\frac{dU}{dx}$.
+
+## Week 6–7: Momentum and rotation
+
+- **Focus:** Impulse, momentum conservation, center of mass, rotational kinematics, torque, and angular momentum.
+- **Reading:** Momentum and rotation chapters.
+- **Practice targets:**
+  - Apply $\Delta \vec{p} = \int \vec{F}\,dt$ to collisions.
+  - Connect linear and rotational motion with $v = r\omega$ and $\tau = I\alpha$.
+- **Lab:** 2D collision carts with video analysis; rotational inertia turntable lab.
+
+??? question "When is angular momentum conserved?"
+    Angular momentum about a point is conserved when the net external torque about that same point is zero.
+
+## Week 8–9: Oscillations and mechanical waves
+
+- **Focus:** Simple harmonic motion (SHM), driven oscillations, resonance, wave speed, superposition, and standing waves.
+- **Reading:** SHM and waves chapters.
+- **Practice targets:**
+  - Derive SHM solutions from $m\ddot{x} + kx = 0$.
+  - Use $v = f\lambda$ to relate frequency and wavelength; interpret boundary conditions.
+- **Lab:** Mass–spring and pendulum resonance studies; string and air-column standing waves.
+
+??? success "Standing wave lab prep"
+    Measure string tension and linear density to predict allowed frequencies. Compare predictions to measured resonant modes.
+
+## Week 10–11: Thermal physics and the first law
+
+- **Focus:** Temperature scales, heat, work in thermodynamic processes, ideal gas model, and energy conservation in macroscopic systems.
+- **Reading:** Thermodynamics chapters (first law, processes, and heat engines).
+- **Practice targets:**
+  - Apply $\Delta U = Q - W$ to isobaric, isochoric, isothermal, and adiabatic processes.
+  - Read and annotate $p$–$V$ diagrams, computing work from areas.
+- **Lab:** Gas law verification and calorimetry experiments.
+
+??? note "Remember units"
+    Keep consistent SI units: Joules for energy and heat, Pascals for pressure, Kelvin for temperature, and cubic meters for volume.
+
+## Week 12–13: Review and synthesis
+
+- **Focus:** Mixed-topic problem solving, experimental uncertainty, and communicating findings.
+- **Activities:**
+  - Capstone lab with full uncertainty propagation and graphical analysis.
+  - Group whiteboard sessions combining dynamics, energy, and rotation.
+
+??? question "How should I prepare for the final?"
+    - Rework one representative problem from each week without notes.
+    - Summarize common solution patterns (free-body diagrams, energy flow charts, and symmetry arguments).
+    - Create a one-page formula sheet focused on relationships you routinely use.
