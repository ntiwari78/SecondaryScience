

# 🔥 Principles of Thermodynamics

This document provides a **comprehensive synthesis of thermodynamics**, a branch of physics concerned with heat, temperature, and energy conversion. It uses a **macroscopic perspective**, focusing on measurable properties like pressure, volume, and temperature.

---

## 1. 🌡️ Foundational Concepts

### 1.1. Nature of Heat

* **Historical View**: Heat once thought to be "caloric" fluid.
* **Modern View**: Heat is a form of energy.
* **Key Experiment**: Count Rumford (1798) showed mechanical work generates heat (e.g., cannon boring), disproving caloric theory.

### 1.2. Thermodynamic vs. Mechanical Systems

* **Mechanics**: Concerns motion under force.
* **Thermodynamics**: Concerns internal macroscopic state.
* **Example**: A bullet’s kinetic energy becomes heat on impact — raising internal energy and temperature.

---

## 2. ⚖️ Laws of Thermodynamics

### 2.1. Zeroth Law: Thermal Equilibrium

* **Statement**: If A = B and B = C in thermal equilibrium, then A = C.
* **Implication**: Defines **temperature** as a measurable property.
* **Walls**:

  * *Adiabatic*: No heat transfer.
  * *Diathermic*: Allows heat flow.

### 2.2. First Law: Conservation of Energy

* **Formula**:

  ```math
  ∆Q = ∆U + ∆W
  ```

  * ∆Q: Heat added to the system
  * ∆U: Change in internal energy
  * ∆W: Work done by the system
* **Properties**:

  * `∆U`: Path-independent (state variable).
  * `∆Q`, `∆W`: Path-dependent (process variables).

### 2.3. Second Law: Direction and Limitations

* **Kelvin-Planck**: No engine can convert all heat into work.
* **Clausius**: Heat can't flow from cold to hot without work.
* **Concepts**:

  * Reversible process: Ideal, quasi-static, no dissipation.
  * Irreversible process: Real, includes friction, turbulence.

---

## 3. 🧮 Core Thermodynamic Quantities

### 3.1. Internal Energy, Heat, Work

* **Internal Energy (U)**: Sum of kinetic + potential energy of particles.
* **Heat (Q)**: Energy due to temperature difference (not stored).
* **Work (W)**: Energy transfer by force (e.g., piston compression).

### 3.2. State Variables

* **Extensive**: Depend on system size (e.g., U, V, mass).
* **Intensive**: Independent of size (e.g., T, P, ρ).
* **Equation of State**:

  ```math
  PV = µRT
  ```

### 3.3. Specific Heat

* **Specific Heat (s)**:

  ```math
  s = \frac{1}{m} \cdot \frac{∆Q}{∆T} \quad [\text{J kg}^{-1} \text{K}^{-1}]
  ```
* **Molar Heat Capacity (C)**:

  ```math
  C = \frac{1}{µ} \cdot \frac{∆Q}{∆T} \quad [\text{J mol}^{-1} \text{K}^{-1}]
  ```
* **Key Relations**:

  * For solids: ( C = 3R ) (equipartition of energy).
  * For gases: ( C_P - C_V = R )

---

## 4. 🔁 Thermodynamic Processes

| **Process** | **Definition**            | **Implication for Ideal Gas**       |
| ----------- | ------------------------- | ----------------------------------- |
| Isothermal  | ∆T = 0                    | PV = const, ∆U = 0, Q = W           |
| Adiabatic   | Q = 0                     | PV^γ = const, W = −∆U               |
| Isochoric   | ∆V = 0                    | W = 0, Q = ∆U                       |
| Isobaric    | ∆P = 0                    | W = P∆V, Q = ∆U + W                 |
| Cyclic      | System returns to initial | ∆U = 0, Q = W (net heat = net work) |

* **Quasi-static**: Infinitely slow, always near equilibrium.

---

## 5. 🔁 Reversibility and the Carnot Engine

### 5.1. Reversibility

* **Reversible**: No net change in system + surroundings; quasi-static and no dissipation.
* **Irreversible**:

  * Non-equilibrium transitions
  * Friction, turbulence

### 5.2. Carnot Engine: Max Efficiency

* **Cycle**:

  1. Isothermal Expansion at T₁ (absorbs Q₁)
  2. Adiabatic Expansion (T₁ → T₂)
  3. Isothermal Compression at T₂ (releases Q₂)
  4. Adiabatic Compression (T₂ → T₁)

* **Efficiency**:

  ```math
  η = 1 - \frac{T_2}{T_1}
  ```

* **Carnot’s Theorem**:

  * No engine > Carnot engine in efficiency between same temperatures.
  * Efficiency is independent of the working substance.

---

## 📚 References

* [Zeroth Law of Thermodynamics – Wikipedia](https://en.wikipedia.org/wiki/Zeroth_law_of_thermodynamics)
* [First Law of Thermodynamics – Wikipedia](https://en.wikipedia.org/wiki/First_law_of_thermodynamics)
* [Second Law of Thermodynamics – Wikipedia](https://en.wikipedia.org/wiki/Second_law_of_thermodynamics)
* [Carnot Cycle – Wikipedia](https://en.wikipedia.org/wiki/Carnot_cycle)
* [Thermodynamic Processes – Wikipedia](https://en.wikipedia.org/wiki/Thermodynamic_process)

