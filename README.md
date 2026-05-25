# 📐 All Electronics Tasks

<div align="center">

![Electronics](https://img.shields.io/badge/Field-Electronics%20%26%20Circuit%20Theory-blue?style=for-the-badge)
![Location](https://img.shields.io/badge/Location-Baku%2C%20Azerbaijan-red?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-English-green?style=for-the-badge)
![Verified](https://img.shields.io/badge/Verified-Physics%20Teacher%20Telman%20Askeraliyev-gold?style=for-the-badge)

**A unified portfolio of electronics laboratory reports, presentations, and engineering projects**  
published on SlideShare, Academia.edu, and Notion.

</div>

---

## 👤 Author

**Mehemmed Verdiyev** — Computer Engineering Student, Khazar University, Baku, Azerbaijan

> All works in this repository were completed as part of an **Electronics & Circuit Theory** laboratory module and are verified by:
>
> 🎓 **Telman Askeraliyev** — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*
> [LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

---

## 📋 Index

| # | Topic | Platform | Authors | Link |
|---|-------|----------|---------|------|
| 01 | [Operational Amplifier](#01--operational-amplifier) | SlideShare | Mahammad | [→ View](https://www.slideshare.net/slideshow/comprehensive-guide-to-operational-amplifiers-in-analog-electronics/287466422) |
| 02 | [Voltage Divider](#02--voltage-divider) | SlideShare | Mahammad  | [→ View](https://www.slideshare.net/slideshow/voltage-divider-circuits-theory-and-practical-implementation/287240591) |
| 03 | [DC Motor Directional Control via Polarity Inversion](#03--dc-motor-directional-control-via-polarity-inversion) | Academia.edu | Mahammad | [→ View](https://www.academia.edu/165822962/DC_Motor_Directional_Control_via_Polarity_Inversion?source=swp_share) |
| 04 | [Inductor Fundamentals](#04--inductor-fundamentals) | SlideShare | Mahammad  | [→ View](https://www.slideshare.net/slideshow/inductor-fundamentals-principles-construction-and-applications-in-modern-electronics/286873535) |
| 05 | [Series vs Parallel Circuit Analysis](#05--series-vs-parallel-circuit-analysis) | SlideShare | Mahammad  | [→ View](https://glaze-cuckoo-f03.notion.site/ELECTRONIC-TASK-Series-vs-Parallel-Circuit-Analysis-By-Hidayet-Hesenli-Ramal-Demirli-Nezrin-Serbe-32603a1c6703803cae98f449a4e151ca?source=copy_link) |
| 06 | [Capacitors: Structure and Functionality](#06--capacitors-structure-and-functionality) | SlideShare | Mahammad | [→ View](https://www.slideshare.net/slideshow/capacitors-structure-and-functionality-pdf/286543198) |

---

## 📚 Detailed Entries

---

### 01 · Operational Amplifier

> **Platform:** SlideShare · **Type:** Comprehensive Guide · **Field:** Analog Electronics

**🔗 Link:** https://www.slideshare.net/slideshow/comprehensive-guide-to-operational-amplifiers-in-analog-electronics/287466422

**Authors:** Hidayet Hesenli · Ramal Damirli · **Mehemmed Verdiyev** · Ferid Elekberov

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **What is an Op-Amp** — voltage-amplifying device with differential inputs (V⁺, V⁻) and single output
- **Ideal Op-Amp Properties** — infinite input impedance, zero output impedance, infinite open-loop gain (A_OL → ∞), infinite bandwidth
- **Internal Structure** — differential input stage, voltage amplification stage, output stage
- **Open-Loop vs Closed-Loop** — behaviour with and without negative feedback
- **Inverting Amplifier** — gain formula: `A_V = −R_f / R_in`; signal is amplified and phase-inverted
- **Non-Inverting Amplifier** — gain formula: `A_V = 1 + R_f / R_in`; no phase inversion
- **Voltage Follower (Unity Gain Buffer)** — `A_V = 1`; used for impedance matching
- **Summing Amplifier** — weighted addition of multiple input signals
- **Differentiator & Integrator** — frequency-domain signal processing using capacitors
- **Comparator Mode** — op-amp without feedback as a threshold detector
- **Feedback Principles** — negative feedback for stability, gain control, and linearity
- **Practical Applications** — audio amplifiers, signal conditioning, ADC drivers, active filters, instrumentation

#### Key Equations

| Configuration | Gain Formula |
|---------------|-------------|
| Inverting Amplifier | `A_V = −R_f / R_in` |
| Non-Inverting Amplifier | `A_V = 1 + R_f / R_in` |
| Voltage Follower | `A_V = 1` |
| Gain in dB | `A_dB = 20 · log₁₀(│A_V│)` |
| Differential Input | `V_out = A_OL · (V⁺ − V⁻)` |

#### Subject
```
Field    : Electronics / Analog Circuit Design
Type     : Comprehensive Educational Guide
Language : English
Location : Azerbaijan, Baku
```

---

### 02 · Voltage Divider

> **Platform:** SlideShare · **Type:** Technical Report · **Field:** Circuit Theory

**🔗 Link:** https://www.slideshare.net/slideshow/voltage-divider-circuits-theory-and-practical-implementation/287240591

**Authors:** Hidayet Hesenli · Ramal Damirli · **Mehemmed Verdiyev** · Agshin Balayev · Farid Elekberov

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **Voltage Divider Principle** — two or more resistors in series used to produce a fraction of the supply voltage
- **Core Formula** — `V_out = V_in × R₂ / (R₁ + R₂)`
- **Loaded vs Unloaded Divider** — effect of load resistance on output voltage accuracy
- **Practical Design Considerations** — choosing resistor ratios, power ratings, tolerance effects
- **Potentiometer as a Divider** — variable output using a wiper contact
- **Applications in Sensor Circuits** — combining with LDR, NTC thermistor, or other variable resistors
- **Biasing Networks** — use in transistor and op-amp bias circuits
- **Signal Level Shifting** — attenuating high-voltage signals to ADC-safe levels
- **Practical Lab Measurements** — measured vs theoretical output voltages, error analysis

#### Key Equations

| Quantity | Formula |
|----------|---------|
| Output Voltage | `V_out = V_in × R₂ / (R₁ + R₂)` |
| With Load | `V_out = V_in × (R₂ ‖ R_L) / (R₁ + R₂ ‖ R_L)` |
| Parallel Resistance | `R_parallel = (R₂ × R_L) / (R₂ + R_L)` |
| Current Through Divider | `I = V_in / (R₁ + R₂)` |

#### Subject
```
Field    : Electronics / Circuit Theory
Type     : Technical Laboratory Report
Language : English
Location : Azerbaijan, Baku
```

---

### 03 · DC Motor Directional Control via Polarity Inversion

> **Platform:** Academia.edu · **Type:** Technical Laboratory Report · **Field:** Electromechanics / Embedded Systems

**🔗 Link:** https://www.academia.edu/165822962/DC_Motor_Directional_Control_via_Polarity_Inversion?source=swp_share

**Authors:** Hidayet Hesenli · Ramal Damirli · **Mehemmed Verdiyev**

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **DC Motor Operating Principle** — Lorentz force on a current-carrying conductor in a magnetic field produces rotational torque
- **Polarity Inversion** — reversing the voltage polarity across the motor terminals reverses the direction of current → reverses rotation
- **Manual Polarity Switching** — SPDT or DPDT switch configurations that swap V+ and GND connections
- **H-Bridge Circuit** — four-switch topology (transistors or MOSFETs) enabling electronic forward/reverse/brake/coast control
- **H-Bridge Truth Table** — switch states for CW, CCW, brake, and coast modes
- **Flyback Diodes** — protection against inductive voltage spikes when the motor is switched off
- **PWM Speed Control** — combining direction control with pulse-width modulation for variable speed
- **Practical Lab Implementation** — breadboard assembly, measurements, oscilloscope waveforms
- **Safety Considerations** — current limiting, heat dissipation, motor stall current

#### H-Bridge Logic Table

| S1 | S2 | S3 | S4 | Motor State |
|----|----|----|-----|------------|
| ON | OFF | OFF | ON | Forward (CW) |
| OFF | ON | ON | OFF | Reverse (CCW) |
| ON | OFF | ON | OFF | Brake (short) |
| OFF | OFF | OFF | OFF | Coast (free) |

#### Subject
```
Field    : Electronics / Electromechanics / Embedded Systems
Type     : Technical Laboratory Report
Platform : Academia.edu
Language : English
Location : Azerbaijan, Baku
```

---

### 04 · Inductor Fundamentals

> **Platform:** SlideShare · **Type:** Technical Report · **Field:** Electromagnetic Theory

**🔗 Link:** https://www.slideshare.net/slideshow/inductor-fundamentals-principles-construction-and-applications-in-modern-electronics/286873535

**Authors:** Hidayet Hesenli · Ramal Damirli · **Mehemmed Verdiyev**

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **Inductor Fundamentals** — a passive two-terminal component that stores energy in a magnetic field when current flows through it
- **Lenz's Law & Back-EMF** — induced voltage opposes the change in current: `V_L = L · dI/dt`
- **Inductance Units** — Henry (H), millihenry (mH), microhenry (μH)
- **Magnetic Flux** — `Φ = L · I` — relationship between flux, inductance, and current
- **Energy Storage** — `W = ½ · L · I²` — energy stored in the magnetic field
- **Construction** — wire coil wound around a core; core material determines inductance range
- **Core Types** — Air core (low L, high-frequency), Iron core (high L, power), Ferrite core (RF/switching), Toroidal (self-shielding)
- **Key Selection Parameters**:
  - **DCR** — DC resistance; lower is better for efficiency
  - **Saturation Current** — maximum current before the core saturates and inductance drops
  - **Q-factor** — quality factor: ratio of reactive to resistive impedance
  - **SRF** — self-resonant frequency above which the inductor behaves capacitively
- **Inductive Reactance** — `X_L = 2π · f · L` — impedance increases with frequency
- **Series & Parallel Inductors** — `L_series = L₁ + L₂`; `1/L_parallel = 1/L₁ + 1/L₂`
- **Applications** — power supply filtering, chokes, LC tank circuits, transformers, EMI suppression, RF tuning

#### Key Equations

| Quantity | Formula |
|----------|---------|
| Induced Voltage | `V_L = L · dI/dt` |
| Magnetic Flux | `Φ = L · I` |
| Stored Energy | `W = ½ · L · I²` |
| Inductive Reactance | `X_L = 2π · f · L` |
| Series Inductance | `L_total = L₁ + L₂ + … + Lₙ` |
| Parallel Inductance | `1/L_total = 1/L₁ + 1/L₂ + … + 1/Lₙ` |

#### Core Type Comparison

| Core Type | Inductance Range | Frequency Range | Best Use |
|-----------|-----------------|-----------------|----------|
| Air Core | Low | Very High (RF) | RF circuits, oscillators |
| Iron Core | Very High | Low (power) | Transformers, power filters |
| Ferrite Core | Medium–High | Medium–High | Switching supplies, EMI chokes |
| Toroidal | High | Medium | Self-shielded power inductors |

#### Subject
```
Field    : Electronics / Electromagnetic Theory
Type     : Technical Laboratory Report
Language : English
Location : Azerbaijan, Baku
```

---

### 05 · Series vs Parallel Circuit Analysis

> **Platform:** Notion · **Type:** Electronic Task / Workspace · **Field:** Circuit Theory

**🔗 Link:** https://glaze-cuckoo-f03.notion.site/ELECTRONIC-TASK-Series-vs-Parallel-Circuit-Analysis-By-Hidayet-Hesenli-Ramal-Demirli-Nezrin-Serbe-32603a1c6703803cae98f449a4e151ca?source=copy_link

**Authors:** Hidayet Hesenli · Ramal Demirli · **Mehemmed Verdiyev** · Nezrin Serbetli

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **Series Circuit Fundamentals** — single current path; same current flows through all components
- **Parallel Circuit Fundamentals** — multiple current paths; same voltage across all branches
- **Kirchhoff's Voltage Law (KVL)** — sum of all voltage drops around a closed loop equals zero
- **Kirchhoff's Current Law (KCL)** — sum of currents entering a node equals sum leaving it
- **Total Resistance Calculations** — series: `R_total = R₁ + R₂ + …`; parallel: `1/R_total = 1/R₁ + 1/R₂ + …`
- **Voltage Distribution** — in series: voltage divides proportionally to resistance
- **Current Distribution** — in parallel: current divides inversely proportional to resistance
- **Power in Each Configuration** — `P = V²/R = I²R = V·I`; total power analysis
- **Practical Circuit Measurements** — multimeter readings of V, I, R for both configurations
- **Real-World Applications** — household wiring (parallel), series battery strings, LED strings

#### Series vs Parallel — At a Glance

| Property | Series | Parallel |
|----------|--------|----------|
| Current | Same through all | Splits across branches |
| Voltage | Splits across components | Same across all |
| Total Resistance | `R₁ + R₂ + …` (always > any single R) | Always < smallest R |
| Failure behaviour | One open = all fail | One open = others still work |
| Application | Voltage dividers, fuses | Household wiring, battery banks |

#### Key Equations

| Quantity | Series | Parallel |
|----------|--------|----------|
| Total Resistance | `R_T = R₁ + R₂ + R₃` | `1/R_T = 1/R₁ + 1/R₂ + 1/R₃` |
| Current | `I = V_total / R_T` (same everywhere) | `I_total = I₁ + I₂ + I₃` |
| Voltage | `V_total = V₁ + V₂ + V₃` | `V = V₁ = V₂ = V₃` |
| Power | `P_total = P₁ + P₂ + P₃` | `P_total = P₁ + P₂ + P₃` |

#### Subject
```
Field    : Electronics / Circuit Theory
Type     : Electronic Task — Live Notion Workspace
Language : English
Location : Azerbaijan, Baku
```

---

### 06 · Capacitors: Structure and Functionality

> **Platform:** SlideShare · **Type:** Educational Presentation · **Field:** Passive Components

**🔗 Link:** https://www.slideshare.net/slideshow/capacitors-structure-and-functionality-pdf/286543198

**Authors:** Hidayet Hesenli · Ramal Demirli · **Mehemmed Verdiyev** · Nezrin Serbetli

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku *(Fizika Müəllimi)*  
[LinkedIn](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) · [Instagram](https://www.instagram.com/physics_teacher_azerbaijan)

#### Topics Covered

- **What is a Capacitor** — passive component that stores electrical energy in an electric field between two conductive plates
- **Physical Structure** — two conductive plates (electrodes) separated by a dielectric insulator
- **Charging Behaviour** — when connected to a voltage source, positive and negative charges accumulate on opposite plates; current flows until `V_cap = V_source`
- **Discharging Behaviour** — stored energy released when a load is connected; exponential discharge curve
- **Capacitance Formula** — `C = ε · A / d` (permittivity × plate area ÷ plate separation)
- **Energy Storage** — `W = ½ · C · V²`
- **Capacitive Reactance** — `X_C = 1 / (2π · f · C)` — impedance decreases with frequency (opposite of inductor)
- **RC Time Constant** — `τ = R · C` — time for capacitor to charge to ~63.2% of source voltage
- **Capacitor Types**:
  - **Ceramic** — small, non-polarised, stable, for decoupling and filtering
  - **Electrolytic** — large capacitance, polarised, for bulk energy storage and power supply filtering
  - **Film** — high precision, low ESR, for timing and audio circuits
  - **Tantalum** — compact, stable, polarised, for precision filtering
- **Series & Parallel Capacitors** — parallel: `C_total = C₁ + C₂`; series: `1/C_total = 1/C₁ + 1/C₂`
- **Applications** — power supply smoothing & filtering, timing circuits (RC oscillators), signal coupling & decoupling, energy storage (camera flash), motor start circuits

#### Key Equations

| Quantity | Formula |
|----------|---------|
| Capacitance | `C = ε · A / d` |
| Stored Energy | `W = ½ · C · V²` |
| Capacitive Reactance | `X_C = 1 / (2π · f · C)` |
| RC Time Constant | `τ = R · C` |
| Charge Stored | `Q = C · V` |
| Parallel Capacitance | `C_T = C₁ + C₂ + C₃` |
| Series Capacitance | `1/C_T = 1/C₁ + 1/C₂ + 1/C₃` |

#### Capacitor Type Comparison

| Type | Polarised | Capacitance Range | Key Strength | Typical Use |
|------|-----------|------------------|--------------|-------------|
| Ceramic | No | pF – μF | Stable, cheap | Decoupling, filtering |
| Electrolytic | Yes | μF – mF | Large capacitance | PSU bulk filtering |
| Film | No | nF – μF | Low ESR, precise | Timing, audio |
| Tantalum | Yes | μF range | Compact, stable | Precision filtering |

#### Subject
```
Field    : Electronics / Passive Components
Type     : Educational Presentation
Language : English
Location : Azerbaijan, Baku
```

---

## 🔖 Verification

All works in this portfolio are verified by:

| | |
|---|---|
| **Name** | Telman Askeraliyev |
| **Title** | Physics Teacher — Azerbaijan, Baku *(Fizika Müəllimi)* |
| **LinkedIn** | [physics-teacher-azerbaijan-telman-askeraliyev](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/) |
| **Instagram** | [@physics_teacher_azerbaijan](https://www.instagram.com/physics_teacher_azerbaijan) |

---

## 📊 Portfolio Stats

![Topics](https://img.shields.io/badge/Topics-6-blue?style=flat-square)
![Platform SlideShare](https://img.shields.io/badge/SlideShare-4%20Reports-orange?style=flat-square)
![Platform Academia](https://img.shields.io/badge/Academia.edu-1%20Report-purple?style=flat-square)
![Platform Notion](https://img.shields.io/badge/Notion-1%20Workspace-black?style=flat-square)

---

<div align="center">

*Electronics & Circuit Theory Laboratory Module — Khazar University, Baku, Azerbaijan*

</div>
