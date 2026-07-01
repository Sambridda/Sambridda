# Sambridda Ranabhat
**Mechatronics Engineering Final Year · Industrial Automation · Embedded Systems**

Kathmandu, Nepal · sambridda.ranabhat@gmail.com · [LinkedIn](https://linkedin.com/in/sambridda-ranabhat)

---

I build things that work in production environments — not just on a bench. My engineering background spans industrial automation, embedded hardware, and thermal-fluid system design, with a strong bias toward applied, hands-on work over purely academic exercises.

Currently finishing a B.Tech in Mechatronics Engineering (KIIT University, India) with a minor in Finance. Interning at **Mechatronics Engineering Pvt. Ltd. (MEPL)**, Kathmandu, where I work across live industrial projects — from PLC ladder logic and electrical documentation to control panel design and site commissioning.

---

## Published Work

**Velocity-Constrained Hydronics (VCH) Sizing Framework**  
*Open-source engineering handbook · Zenodo · DOI: [[10.5281/zenodo.21009246](https://doi.org/10.5281/zenodo.21009246)]*

A 180-page industrial design methodology covering an 11-step mathematical procedure for sizing hydronic thermal regulation loops. Includes 8 technical appendices spanning thermofluid property tables, control architecture diagrams, SCADA stack illustrations, break-even analysis, and a fully resolved production-ready case study.

Written to fill a methodological gap encountered during an active industrial internship — no standardised accessible method existed for velocity-constrained hydronic sizing. The framework was subsequently applied to a real pharmaceutical-grade production deployment.

---

## Core Competencies

### **Industrial Automation**
![Coolmay](https://img.shields.io/badge/Coolmay_PLC--HMI-2C3E50?style=flat-square)
![Mitsubishi](https://img.shields.io/badge/Mitsubishi_PLC-E60012?style=flat-square)
![CODESYS](https://img.shields.io/badge/CODESYS-0077B5?style=flat-square)
![GXWorks2](https://img.shields.io/badge/GX_Works2-E60012?style=flat-square)
![Ladder Logic](https://img.shields.io/badge/Ladder_Logic_&_ST-IEC_61131--3-3498DB?style=flat-square)
![RS485](https://img.shields.io/badge/RS485-555555?style=flat-square)

### **Embedded Systems & Hardware**
![ESP32](https://img.shields.io/badge/ESP32-323232?style=flat-square&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-412F1F?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad_PCB-314CB0?style=flat-square)
![Wireless](https://img.shields.io/badge/Wireless-WiFi_|_2.4GHz_|_433MHz_|_HC--12-E67E22?style=flat-square)
![Instrumentation](https://img.shields.io/badge/Lab_Equipment-Oscilloscope_|_Function_Gen-9B59B6?style=flat-square)

### **CAD**
![SolidWorks](https://img.shields.io/badge/SolidWorks-CC0000?style=flat-square)
![AutoCAD Electrical](https://img.shields.io/badge/AutoCAD_Electrical-E51937?style=flat-square)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF7300?style=flat-square)
![QElectroTech](https://img.shields.io/badge/QElectroTech-2ECC71?style=flat-square)
![FluidSIM](https://img.shields.io/badge/FluidSIM-1ABC9C?style=flat-square)

### **System Designing**
![Electrical Sizing](https://img.shields.io/badge/Electrical_Design-Component_&_Wire_Sizing-34495E?style=flat-square)
![Hydronic](https://img.shields.io/badge/Hydronic_Systems_(VCH)-1ABC9C?style=flat-square)
![P&ID](https://img.shields.io/badge/P%26ID_Design-2980B9?style=flat-square)

### **Workshop**
![G-Code](https://img.shields.io/badge/G--Code_CNC-555555?style=flat-square)
![Fabrication](https://img.shields.io/badge/Workshop-Arc_Welding_|_Soldering-D35400?style=flat-square)

### **Programming**
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## Engineering Projects

### [Control-System-for-Seismic-Wave-Generator](https://github.com/Sambridda/Control-System-for-Seismic-Wave-Generator)
*MEPL · Kathmandu, Nepal · 2026 · Active (Proposal & Design)*
Feedforward–feedback control architecture for a PLC-supervised asymmetric hydraulic cylinder, driving prescribed triangular and sinusoidal displacement trajectories via proportional flow and pressure valves.
- Derived the governing orifice flow relationship and normalized valve command equations ($u_{dcv} \in [-1,1]$, $u_{pcv} \in [0,1]$) from first principles, validated against Merritt's hydraulic control theory and ISO 4411/10770-1
- Synthesized closed-form feedforward trajectory equations for triangular and sinusoidal motion under two independent PCV architectures (fixed relief vs. active proportional pressure control)
- Designed a cascaded feedforward + PID compensation layer with anti-windup and deadband correction to close the residual position-tracking gap
- Analytically bounded achievable operating frequency by resolving four competing constraints (hydraulic resonance, pump flow limit, inertial force limit, valve bandwidth) rather than relying on trial-and-error tuning
- Benchmarked three PLC hardware platforms against realistic (not nominal 1 kHz) loop-rate requirements to guide a cost-effective hardware selection for the Nepal market

### [Palm-Oil-Systems-Design](https://github.com/Sambridda/palm-oil-systems-design)
*MEPL · Kathmandu, Nepal · 2026 · Active (Design & Verification)*

Industrial thermal processing and automation architecture for a multi-tank palm oil melting and trim-heating facility, scaling output using a self-authored sizing framework and smart PLC queuing.

- Sized and modeled multi-phase thermal dynamics for three 10 kL storage vessels and one 5 kL trim-heating tank using the self-authored VCH Sizing Framework (2nd Ed.)
- Developed PLC automation logic using a Dynamic Upper Thermal Boundary equation ($T_f$) to prevent thermal overshooting and system line stress
- Coded volume- and temperature-weighted priority queuing algorithms ($S_{\text{casual}}$ / $S_{\text{immediate}}$) to coordinate an overlapping, staggered multi-tank melt sequence
- Engineered a single-pump solar thermal integration circuit backed by a 36 kW auxiliary electric array to offset 61.46% of the daily energy budget
- Analyzed a 4-case pipe and coil diameter matrix (1" and 1.5" NPS) to resolve material cost constraints without sacrificing system throughput

### [Pharmaceutical-Grade Purified Water Treatment System](https://github.com/Sambridda/Prarmaceutical-Grade-Purified-Water-Treatment-system)
*MEPL · Butwal, Nepal · 2026 · Active (Commissioning)*

Control system upgrade for a GMP/GEP-compliant purified water production facility — dual-pass RO, electro-deionization, and UV sterilization for pharmaceutical-grade internal use.

- Full electrical documentation across 6 motors, 4 VFD zones, and 53 instrument nodes
- 10-sheet AutoCAD Electrical schematic set — motor circuits, PLC I/O, VFD logic, pneumatic outputs
- Control panel design: DIN rail layout, HMI dimensional fit, thermal planning
- Instrumentation logic audit — identified and resolved sensor placement issues in original proposal
- Mitsubishi FX1NA-24MR-DS PLC programming assigned for commissioning phase

---

### [Automated Peristaltic Pump Dispensing System](https://github.com/Sambridda/Peristaltic-Pump)
*MEPL · Kathmandu · 2026 · Complete*

Precision liquid dosing system for ophthalmic solution measurement. PLC-controlled stepper motor drive with experimental K-factor calibration engine — accurate to ±0.1 mL across the full 5–20 mL operating range.

- Sole designer and programmer — hardware, ladder logic, HMI
- Resolved 4 real integration failures during development: HMI–PLC race condition, floating-point data type mismatch, CPU math halt prevention, and retentive memory leak
- Validated across multi-point linearity test: 5, 7.5, 10, 15, and 20 mL

---

### [Decentralised Smart Home Water Automation (WACPv4)](https://github.com/Sambridda/Water-Automation-Control)
*Independent · In Development*

Three-node wireless automation loop for residential water management. Custom PCBs centred on ESP32 nodes with HC-12 long-range radio telemetry. Written a lightweight collision-resistant custom protocol for cross-node data handling across obstructed sight lines. Retro HMI with real-time storage and line telemetry display.

---

## Education

**B.Tech — Mechatronics Engineering**  
KIIT University, Bhubaneswar, India · Expected July 2027  
Minor: Finance and Money Analysis

**Cambridge A-Levels**  
St. Xavier's College, Kathmandu · 2022  
Mathematics · Chemistry · Physics & EGP

---

## Languages

| Language | Proficiency |
|----------|-------------|
| English | Full professional — primary academic language since Grade 1; A-Levels and B.Tech entirely in English (IELTS 7.5, 2023) |
| Nepali | Native |
| Hindi | Working proficiency (receptive B1) |
| German | Elementary (A2, self-studied) |

---

*Engineering is not about knowing the method. It's about knowing when no method exists — and writing one.*
