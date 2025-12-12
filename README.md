# Vehicle Design & Battery Packaging

## 📌 Project Overview
This project covers the architectural design of vehicle subsystems, focusing on regulatory compliance, ergonomics, and electric powertrain integration.

## 🚗 Key Components

### 1. Wheel Arch & Ground Clearance Sizing
* **Vehicle:** Volkswagen Golf Mk4.
* **Method:** Geometric sizing of front/rear wheel arches considering steering kinematics (Ackermann geometry), suspension travel, and tire envelope (225/40 R18).
* **Load Analysis:** Calculated ground clearance variations under different loading conditions (passengers + luggage) to ensure no interference.

### 2. EV Battery Pack Design
* **Target:** 800V High-Performance Battery Pack (96 kWh).
* **Architecture:** Cell-to-Module (CTM) design using **Pouch Cells** (LG Chem E66A).
* **Configuration:** 2s2p module arrangement to achieve target voltage and capacity.
* **Thermal & Structural:** Designed a liquid cooling plate system and a rigid ABS/Steel housing to ensure structural integrity and thermal management.
* **Performance:** Achieved a gravimetric energy density of **204.5 Wh/kg** at the pack level.

## 💻 Tech Stack
* **Methodology:** CAD conception, Geometric dimensioning and tolerancing (GD&T).
* **Tools:** CAD (Solidworks/Catia implied), Analytical calculation.
