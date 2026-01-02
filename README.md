# Car Body Design & Automotive Engineering Projects

---

## 📂 Repository Contents

### 1. Wheel Arch and Ground Clearance Sizing
**Objective:** Establish dimensions for front/rear wheel arches and ground clearance for a commercial vehicle (Volkswagen Golf 4) under various load conditions.

* **Vehicle Parameters:** Based on VW Golf 4 (2003) using **225/40 R18** tires.
* **Methodology:**
    * **Steering Analysis:** Computed kinematic steering dimensions (inner angle $\delta_2 = 24.80^\circ$, outer angle $\delta_1 = 32.77^\circ$) to determine wheel arch volume.
    * **Clearance:** Included a **25 mm** gap for snow chains and dirt accumulation.
    * **Load Analysis:** Calculated ground clearance displacement under 6 distinct load cases (empty to full capacity with 5 passengers + luggage).
* **Key Results:**
    * **Front Axle:** Max displacement of 10.92 mm under full load.
    * **Rear Axle:** Max displacement of 32.48 mm under full load, requiring larger vertical clearance.
    * **Design:** Final arch designs accommodate suspension travel (35 mm) plus computed displacements.

### 2. Battery Dimensioning for Electric Vehicles
**Objective:** Design a high-performance **800V, 96 kWh** battery pack with a focus on layout, thermal management, and energy density.

* **Tech Specs:**
    * **Configuration:** Cell-to-Module (CTM) architecture.
    * **Cell Type:** **LG Chem E66A** Pouch cells (65 Ah capacity, 259 Wh/kg).
    * **Module Layout:** 108 cells in series, 1 in parallel (108s1p) to achieve 400V per module.
    * **Pack Layout:** 4 modules connected in **2s2p** to reach 800V target.
* **Mechanical & Thermal Design:**
    * **Cooling:** Liquid cooling plates with aluminum sheets wrapped around cells for heat transfer.
    * **Housing:** ABS plastic case for modules with a steel bottom sheet for structural rigidity.
* **Performance Metrics:**
    * **Gravimetric Density:** 204.5 Wh/kg (Pack level).
    * **Volumetric Efficiency:** 77.2%.

### 3. FEM Modeling and Modal Analysis
**Objective:** Perform modal analysis on a cantilever beam to correlate FEM simulations with experimental test bench data.

* **Setup:**
    * Aluminum beam clamped at one end, excited by an instrumented hammer.
    * Response measured via accelerometer and analyzed in MATLAB.
* **Simulation:**
    * Beam discretized into **28 elements**.
    * Solved the eigenproblem $([K] - \lambda[M] = 0)$ to find natural frequencies.
    * Tuned **Young's Modulus ($E = 65 \text{ GPa}$)** and **Damping ($\xi = 0.01$)** to match experimental peaks.
* **Results:**
    * Accurate correlation achieved in the **0–400 Hz** frequency range.
    * Verified structural behavior through Bode plot comparison.

---

## 🛠️ Tools & Technologies
* **CAD Modeling:** Used for battery pack and wheel arch rendering.
* **MATLAB:** Used for FEM discretization, state-space representation, and frequency response plotting.
* **FEM:** Finite Element Method for structural analysis.
