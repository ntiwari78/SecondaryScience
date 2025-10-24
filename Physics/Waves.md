

# Core Concepts in String and Sound Waves

## Executive Summary

This document synthesizes the fundamental principles governing **string** and **sound waves**.
**Wave motion** is a mechanism that transports **energy** without transporting matter.
Waves are classified as:

* **Mechanical waves** (require a medium, e.g., sound, seismic waves)
* **Non-mechanical waves** (can propagate through a vacuum, e.g., light, radio)

Waves are also categorized by the direction of particle motion relative to propagation:

* **Transverse**: motion perpendicular to propagation (e.g., waves on a string)
* **Longitudinal**: motion parallel to propagation (e.g., sound waves)

Key phenomena include **interference**, **beats**, **stationary waves**, and the **Doppler Effect**.
Sound intensity is expressed logarithmically in **decibels (dB)**, while **temperature**, **medium properties**, and **density** determine wave speed.

---

## 1.0 Fundamental Principles of Wave Motion

### 1.1 Definition and Energy Transport

Wave motion transfers energy without mass transfer.
Example:

* **Letter delivery** → particle transport
* **Telephone communication** → wave transport

### 1.2 Wave Classification

| **Basis**                    | **Types**      | **Description & Examples**                     |
| ---------------------------- | -------------- | ---------------------------------------------- |
| **Medium Necessity**         | Mechanical     | Require a medium (sound, water, seismic waves) |
|                              | Non-mechanical | No medium needed (light, radio)                |
| **Energy Propagation**       | Progressive    | Energy travels with constant velocity          |
|                              | Stationary     | Energy does not propagate (standing waves)     |
| **Direction of Propagation** | 1D             | Wave on a string                               |
|                              | 2D             | Ripples on water                               |
|                              | 3D             | Sound from a point source                      |
| **Medium Particle Motion**   | Transverse     | Motion ⟂ propagation                           |
|                              | Longitudinal   | Motion ∥ propagation                           |

### 1.3 Characteristics of Transverse and Longitudinal Waves

**Transverse Waves**

* Occur in solids and liquid surfaces
* Particle motion: [Simple Harmonic Motion (SHM)](https://en.wikipedia.org/wiki/Simple_harmonic_motion)
* Key terms: **Crest**, **Trough**

**Longitudinal Waves**

* Occur in gases and fluids
* Alternate **compressions** and **rarefactions**
* Example: **Sound waves in air** (~1 Pa variation vs 10⁵ Pa atmosphere)

### 1.4 Key Wave Parameters and Equations

| Parameter         | Symbol   | Description                           |
| ----------------- | -------- | ------------------------------------- |
| Wavelength        | λ        | Distance between same-phase particles |
| Frequency         | f or n   | Vibrations per second                 |
| Time Period       | T        | Time for one wavelength               |
| Amplitude         | A        | Max displacement                      |
| Angular Frequency | ω = 2πn  | —                                     |
| Wave Number       | k = 2π/λ | —                                     |

**Wave Equation**
For a progressive wave moving in +x:

```
y = A sin(ωt - kx)
```

For −x, change the sign.

**Velocity Relations**

* Wave velocity: `v = fλ = ω/k`
* Particle velocity: `v = ∂y/∂t = Aω cos(ωt - kx)`
* Relation: `v_particle = -v_wave * (∂y/∂x)`

---

## 2.0 Wave Dynamics in a Medium

### 2.1 Velocity of Transverse Waves in Strings

```
v = √(T/m)
```

Where:

* **T** = tension
* **m** = linear mass density

**Laws:**

* Tension: `v ∝ √T`
* Mass: `v ∝ 1/√m`
* Radius: `v ∝ 1/r`
* Density: `v ∝ 1/√ρ`

### 2.2 Speed of Longitudinal (Sound) Waves

General formula:

```
v = √(E/ρ)
```

* Solids: `v = √(Y/ρ)` (Young’s Modulus)
* Liquids: `v = √(B/ρ)` (Bulk Modulus)

**Newton’s Formula (Isothermal):**
`v = √(P/ρ)` → 279 m/s (incorrect)

**Laplace’s Correction (Adiabatic):**
`v = √(γP/ρ)` → 331.3 m/s (accurate)

Also:

```
v = √(γRT/M)
```

where `γ` = adiabatic index, `R` = gas constant, `T` = temperature, `M` = molar mass.

### 2.3 Factors Affecting Speed of Sound

* **Temperature:** `v_t ≈ v₀ + 0.61t`
* **Humidity:** ↑ humidity → ↓ density → ↑ velocity
* **Pressure:** no effect at constant temperature
* **Wind:** modifies apparent velocity
* **Frequency:** independent of medium

### 2.4 Intensity and Power

```
I = 2π²f²A²ρv
```

* `I ∝ A²`, `I ∝ f²`
* For point source: `I ∝ 1/r²`

---

## 3.0 Superposition and Wave Interaction

### 3.1 Principle of Superposition

Resultant displacement = vector sum of individual displacements.

### 3.2 Interference

For `y₁ = A₁ sin(ωt - kx)` and `y₂ = A₂ sin(ωt - kx + φ)`

Resultant amplitude:

```
A² = A₁² + A₂² + 2A₁A₂ cosφ
```

Types:

* **Constructive:** φ = 2nπ → `Δx = nλ`
* **Destructive:** φ = (2n+1)π → `Δx = (2n−1)λ/2`

### 3.3 Reflection and Transmission

* **Rigid End:** phase inversion (π)
* **Free End:** no phase change
* **Boundary:**

  * Light → Dense: inverted
  * Dense → Light: upright

---

## 4.0 Stationary (Standing) Waves

### 4.1 Formation and Properties

Superposition of two opposite waves → no energy transport.

* **Nodes**: zero amplitude
* **Antinodes**: maximum amplitude
* Distance between nodes = λ/2

| Property    | Progressive | Stationary                    |
| ----------- | ----------- | ----------------------------- |
| Propagation | Moves       | Fixed                         |
| Energy      | Transmitted | Not transmitted               |
| Amplitude   | Constant    | Varies                        |
| Phase       | Continuous  | 180° out of phase per segment |

### 4.2 Strings Fixed at Both Ends

Allowed wavelengths:

```
L = p(λ/2)
```

Allowed frequencies:

```
f_p = (p/2L)√(T/m)
```

* Fundamental: `f₁ = (1/2L)√(T/m)`
* Harmonics: `f₁, 2f₁, 3f₁, ...`

### 4.3 Air Columns (Organ Pipes)

**Closed Pipe:**
`L = (2m+1)λ/4`, `f = (2m+1)v/4L` → odd harmonics only.

**Open Pipe:**
`L = (m+1)λ/2`, `f = (m+1)v/2L` → all harmonics present.

---

## 5.0 Auditory Phenomena

### 5.1 Beats

Two close frequencies interfere:

```
f_beat = |f₁ − f₂|
```

### 5.2 Doppler Effect

Apparent frequency:

```
n' = n * [(v ± v_w ± v_o) / (v ± v_w ± v_s)]
```

Depends on motion of **source**, **observer**, and **wind**.

| Case              | Apparent Frequency       | Result      |
| ----------------- | ------------------------ | ----------- |
| Source → Observer | n' = n * [v / (v - v_s)] | ↑ frequency |
| Source ← Observer | n' = n * [v / (v + v_s)] | ↓ frequency |
| Observer → Source | n' = n * [(v + v_o) / v] | ↑ frequency |
| Observer ← Source | n' = n * [(v - v_o) / v] | ↓ frequency |

### 5.3 Intensity and Decibel Scale

```
β = 10 log₁₀(I / I₀)
```

where `I₀ = 10⁻¹² W/m²`

* +10 dB = 10× increase in intensity

---

## 6.0 Sound Wave Characteristics and Applications

### 6.1 Displacement vs. Pressure Waves

* **Displacement:** `y = A sin(ωt - kx)`
* **Pressure:** `P = P₀ cos(ωt - kx)` (90° phase difference)
* Pressure amplitude: `P₀ = ρvAω`

### 6.2 Frequency Spectrum

| Type       | Frequency Range | Examples              |
| ---------- | --------------- | --------------------- |
| Infrasonic | < 20 Hz         | Earthquakes           |
| Audible    | 20–20,000 Hz    | Human hearing         |
| Ultrasonic | > 20,000 Hz     | Bats, medical imaging |

### 6.3 Experimental Apparatus

* **Sonometer:** studies [vibrating strings](https://en.wikipedia.org/wiki/Sonometer)
* **Resonance Tube:** measures [speed of sound](https://en.wikipedia.org/wiki/Resonance_tube)
* **Kundt’s Tube:** visualizes [standing waves](https://en.wikipedia.org/wiki/Kundt%27s_tube)
* **Quinck’s Tube:** demonstrates [sound interference](https://en.wikipedia.org/wiki/Quincke%27s_tube)

---

## References

* [Wave Motion – Wikipedia](https://en.wikipedia.org/wiki/Wave)
* [Sound Wave – Wikipedia](https://en.wikipedia.org/wiki/Sound_wave)
* [Simple Harmonic Motion](https://en.wikipedia.org/wiki/Simple_harmonic_motion)
* [Superposition Principle](https://en.wikipedia.org/wiki/Superposition_principle)
* [Interference (Physics)](https://en.wikipedia.org/wiki/Interference)
* [Doppler Effect](https://en.wikipedia.org/wiki/Doppler_effect)
* [Standing Wave](https://en.wikipedia.org/wiki/Standing_wave)
* [Decibel](https://en.wikipedia.org/wiki/Decibel)
* [Acoustics](https://en.wikipedia.org/wiki/Acoustics)
* [Laplace’s Correction](https://en.wikipedia.org/wiki/Speed_of_sound#Laplace's_correction)

