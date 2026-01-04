# 🔋 Fundamentals of Electrochemical Energy Storage  in Batteries.
---

## 1. ⚙️ Electrochemical Foundations

### **Phases**
A **phase** is a region with uniform physical and chemical properties.  
In batteries, typical phases include:
- Solid metal electrode  
- Liquid or solid electrolyte  
- Solid reaction products  

Charge transfer occurs **across phase boundaries**, not within a single phase.

---

### **Dissociation**
Electrolytes dissociate into ions:


AB→A++B−


This creates mobile ions that enable ionic conduction.

---

### **Electrolyte**
A medium containing mobile ions.  
Functions:
- Conduct ions between electrodes  
- Maintain charge neutrality  
- Participate in electrochemical reactions  

Electrolytes conduct **ions**, not electrons.

---

### **Electrode**
An electrode is a **polyphase system**:
- Electron conductor (metal)  
- Ion conductor (electrolyte)

At the interface, **redox reactions** occur:
- **Oxidation** at the anode  
- **Reduction** at the cathode  

---

## 2. ⚡ Electrode Potentials & Cell Voltage

### **Standard Electrode Potential (E°)**
Indicates a species’ tendency to gain or lose electrons.

- Positive E° → strong oxidizing agent (noble metals)  
- Negative E° → strong reducing agent (base metals)

### **Cell Voltage**


Ecell=Ecathode∘−Eanode



This is the theoretical open‑circuit voltage of the cell.

---

## 3. 🔋 Battery Terminology

### **Rated Voltage**
Nominal voltage used for system description.  
Actual voltage varies by ±30% depending on chemistry and SOC.

---

### **Capacity (C\_N)**  
Amount of charge a battery can deliver:


C=I⋅t


Measured in **ampere‑hours (Ah)**.

**N‑hour capacity**:  

IN=CN/N



Example:  
A 20‑hour capacity test uses current \( I_{20} = \frac{C_{20}}{20} \).

---

### **State of Charge (SOC)**


SOC=(Qremaining/Qfull)×100%




---

### **Depth of Discharge (DOD)**



DOD = 1 - SOC




---

### **Self‑Discharge**
Internal chemical reactions reduce stored charge even without load.

---

### **Charge Factor (η\_charge)**



ηcharge=Qdischarged / Qcharged



Represents charging efficiency.

---

## 4. 🔄 Lead‑Acid Battery Chemistry

### **Anode (Oxidation)**



Pb+SO4^2− →  PbSO4+2e−



---

### **Cathode (Reduction)**


PbO2+4H^+ + SO4^2− + 2e^− →  PbSO4 + 2H2O



---

### **Overall Discharge Reaction**




Pb + PbO_2 + 2H_2SO_4  ->  2PbSO_4 + 2H_2O



### Key Theoretical Points
- Both electrodes convert to **PbSO₄** during discharge.  
- Electrolyte concentration decreases → measurable via specific gravity.  
- Reaction is reversible → rechargeable system.

---

## 5. 🔬 General Battery Theory (Extended)

### **Why Batteries Produce Voltage**
Voltage arises from:
- Chemical potential differences  
- Electron affinity differences (E° values)  
- Separation of charges across phases  

---

### **Why Batteries Age**
Main degradation mechanisms:
- Loss of active material  
- Structural changes in electrodes  
- Electrolyte decomposition  
- Formation of passivation layers  
- Side reactions (e.g., gas evolution)  

---

### **Factors Affecting Battery Performance**
- Temperature  
- Discharge rate  
- Aging  
- Internal resistance  
- Electrode surface area  
- Electrolyte concentration  

---

## 6. 📘 Classification of Batteries

### **Primary (Non‑Rechargeable)**
- Alkaline  
- Zinc‑carbon  
- Lithium primary (Li‑SOCl₂, Li‑MnO₂)

### **Secondary (Rechargeable)**
- Lead‑acid  
- Nickel‑cadmium (NiCd)  
- Nickel‑metal hydride (NiMH)  
- Lithium‑ion  
- Lithium iron phosphate (LFP)  
- Sodium‑ion (emerging)

---

## 7. 🧪 Nernst Equation (Advanced Theory)

The electrode potential under non‑standard conditions:


E=  E∘  −  ( RT / nF )ln⁡Q


Where:  
- \( R \) = gas constant  
- \( T \) = temperature  
- \( n \) = electrons transferred  
- \( F \) = Faraday constant  
- \( Q \) = reaction quotient  

This explains how voltage changes with concentration and temperature.

---

## 8. 🧠 Gibbs Free Energy & Battery Voltage

Relationship between cell voltage and energy:


ΔG =  −nFE(cell)


A negative ΔG means the reaction is spontaneous → battery can deliver power.

---

# 🔋 Overview of Battery Types & Batteries Used in Modern Cars  

---

## 1. 🟦 Primary Batteries (Non‑Rechargeable)

Primary batteries are designed for one‑time use. Their chemical reactions are not reversible.

### **1. Alkaline Battery (Zn–MnO₂)**
- **Voltage:** 1.5 V  
- **Chemistry:**  
  - Anode: \( Zn \rightarrow Zn^{2+} + 2e^- \)  
  - Cathode: \( MnO_2 + H_2O + e^- \rightarrow MnOOH + OH^- \)  
- **Pros:** Cheap, long shelf life  
- **Cons:** Not rechargeable  
- **Uses:** Remotes, clocks, toys  

---

### **2. Zinc‑Carbon Battery**
- Older, cheaper version of alkaline  
- Lower capacity  
- Used in low‑drain devices  

---

### **3. Lithium Primary Batteries**
Examples: Li‑SOCl₂, Li‑MnO₂  
- **Voltage:** 3.0–3.6 V  
- **Pros:** Very long shelf life, high energy density  
- **Uses:** Sensors, medical devices, memory backup  

---

## 2. 🟩 Secondary Batteries (Rechargeable)

Rechargeable batteries have reversible chemical reactions.

---

### **1. Lead‑Acid Battery**
- **Voltage:** 2.0–2.1 V per cell  
- **Pros:** Cheap, high surge current  
- **Cons:** Heavy, low energy density  
- **Uses:**  
  - Car starter batteries (12 V)  
  - UPS systems  
  - Industrial forklifts  

**Discharge reactions:**

**Anode (oxidation):**  


\[
Pb + SO_4^{2-} \rightarrow PbSO_4 + 2e^-
\]



**Cathode (reduction):**  


\[
PbO_2 + 4H^+ + SO_4^{2-} + 2e^- \rightarrow PbSO_4 + 2H_2O
\]



**Overall:**  


\[
Pb + PbO_2 + 2H_2SO_4 \rightarrow 2PbSO_4 + 2H_2O
\]



---

### **2. Nickel‑Cadmium (NiCd)**
- **Voltage:** 1.2 V  
- **Pros:** Very robust, long cycle life  
- **Cons:** Cadmium is toxic  
- **Uses:** Aviation, older power tools  

---

### **3. Nickel‑Metal Hydride (NiMH)**
- **Voltage:** 1.2 V  
- **Pros:** Safe, good cycle life  
- **Cons:** Lower energy density than Li‑ion  
- **Uses:**  
  - **Hybrid cars (Toyota Prius)**  
  - Rechargeable AA/AAA cells  

---

### **4. Lithium‑Ion Batteries (Li‑ion)**
Most important rechargeable battery family today.

**Common chemistries:**
- NMC (Nickel‑Manganese‑Cobalt)  
- NCA (Nickel‑Cobalt‑Aluminum)  
- LFP (Lithium Iron Phosphate)  
- LCO (Lithium Cobalt Oxide)  
- LMO (Lithium Manganese Oxide)

**Why Li‑ion dominates:**
- High energy density  
- High voltage (3.6–4.2 V per cell)  
- Good cycle life  
- Lightweight  

---

### **5. Lithium Iron Phosphate (LiFePO₄ / LFP)**
- **Voltage:** 3.2–3.3 V  
- **Pros:** Extremely safe, long cycle life  
- **Cons:** Lower energy density  
- **Uses:**  
  - Electric buses  
  - Home energy storage  
  - Many modern EVs (Tesla, BYD, MG)  

---

### **6. Solid‑State Batteries (Emerging)**
- Solid electrolyte  
- Higher safety  
- Higher energy density  
- Still under development  

---

# 3. 🚗 Batteries Used in Modern Cars

Modern vehicles use **different battery types** depending on the drivetrain.

---

## 🟥 A. Conventional Cars (Petrol/Diesel)

### **Battery Type: Lead‑Acid**
- 12 V system  
- Used for:  
  - Starter motor  
  - Lights  
  - Electronics  
- Chemistry: Pb / PbO₂ with sulfuric acid  

---

## 🟧 B. Hybrid Cars (HEV)

### **Battery Type: NiMH**
Examples: Toyota Prius, Honda Insight  
- **Voltage:** 200–300 V pack  
- **Pros:**  
  - Very long life  
  - Very safe  
  - Handles high charge/discharge cycles  
- **Chemistry:** NiOOH / Metal Hydride  

---

## 🟨 C. Plug‑In Hybrids (PHEV)

### **Battery Type: Lithium‑Ion**
- Higher energy density needed for electric‑only driving  
- Chemistries: NMC, NCA, LFP  

---

## 🟩 D. Fully Electric Cars (EVs)

### **Battery Type: Lithium‑Ion (dominant)**

#### Most common chemistries:
| Chemistry | Used By | Strength |
|----------|---------|----------|
| **NMC** | BMW, VW, Hyundai | Balanced performance |
| **NCA** | Tesla (older models) | High energy density |
| **LFP** | Tesla (newer), BYD, MG | Very safe, long life |
| **LMO** | Nissan Leaf (older) | Good power, lower life |

### **Why Li‑ion is used in EVs**
- High energy density → long range  
- High voltage → efficient power electronics  
- Good cycle life  
- Lightweight  

---

# 4. 🏁 Summary: Evolution Toward EV Batteries

1. **Lead‑acid** → starter batteries  
2. **NiMH** → hybrid vehicles  
3. **Li‑ion (NMC/NCA)** → early EVs  
4. **Li‑ion (LFP)** → modern EVs (safer, cheaper, long life)  
5. **Solid‑state** → future EVs  

---



# 🔋 Lithium-Ion Battery Theory — Diagrams & Explanations

This document summarizes key diagrams and concepts related to lithium-ion batteries, based on educational slides and extended theory. It covers cell construction, operating principles, aging mechanisms, and discharge behavior.

---

## 1. 🧱 Construction of a Lithium-Ion Cell

**Diagram Description:**


| Cu Foil (15 µm) | Graphite Particles | Separator (50–100 µm) | Cathode Particles + Conductive Carbon + Binder | Al Foil (20 µm) |



**Explanation:**

- **Anode side**: Copper foil coated with graphite particles (Li⁺ intercalation host).
- **Separator**: Microporous polymer layer allowing ion flow but preventing short circuits.
- **Cathode side**: Aluminum foil coated with active material (e.g., LiCoO₂, LFP) mixed with conductive carbon and binder.
- **Function**: During discharge, Li⁺ ions move from anode to cathode through the separator; electrons flow through the external circuit.

---

## 2. 🔄 Rocking Chair Mechanism

**Diagram Description:**  
A symbolic rocking chair with Li⁺ ions moving back and forth between two electrodes.

**Explanation:**

- **Intercalation**: Li⁺ ions are reversibly inserted into electrode materials.
- **No lithium plating**: Unlike older chemistries, Li⁺ does not deposit as metal.
- **Volume change**: Electrodes expand/contract slightly during cycling.
- **Efficiency**:
  - Coulombic efficiency ≈ 100% (charge in = charge out)
  - Energy efficiency ≈ 95%

---

## 3. 📉 Voltage vs. Discharge Current

**Diagram Description:**

- **Left graph**: Terminal voltage vs. capacity (Ah) for different discharge currents.
- **Right graph**: Terminal voltage vs. current (A), showing voltage drop with increasing current.
- **Cutoff voltage**: Manufacturer-defined minimum safe voltage.

**Explanation:**

- Higher discharge current → greater voltage drop due to internal resistance.
- Battery capacity appears lower at high current.
- Cutoff voltage prevents over-discharge and damage.

---

## 4. 🧪 Aging Mechanisms in Lithium-Ion Cells

**Diagram Description:**

- Left: Fresh cell with intact particles and conduction paths.
- Right: Aged cell showing:
  - SEI growth
  - Particle fracture
  - Loss of Li⁺
  - Increased resistance
  - Capacity loss

**Explanation:**

- **SEI (Solid Electrolyte Interphase)**: Forms on anode, consumes Li⁺, increases resistance.
- **Mechanical stress**: Volume changes cause particle cracking.
- **Electrolyte degradation**: Loss of additives reduces ionic conductivity.
- **Conduction loss**: Broken particles disconnect from current collectors.
- **Result**: Reduced capacity, higher internal resistance, shorter cycle life.

---

## 5. 📘 Summary of Key Concepts

| Concept                  | Description |
|--------------------------|-------------|
| Intercalation            | Reversible insertion of Li⁺ into electrode materials |
| SEI Layer                | Passivation layer on anode, grows over time |
| Coulombic Efficiency     | Ratio of charge out to charge in (≈100%) |
| Energy Efficiency        | Ratio of energy out to energy in (≈95%) |
| Cutoff Voltage           | Minimum voltage to prevent over-discharge |
| Aging Effects            | SEI growth, Li⁺ loss, particle fracture, conduction loss |

---



# 📘 Theoretical Concepts in Lithium-Ion and Lead-Acid Batteries

This section explains key theoretical principles behind lithium-ion and lead-acid battery behavior, aging, and performance.

---

## 1. ⚛️ Intercalation Mechanism (Lithium-Ion)

- Lithium-ion batteries use **intercalation electrodes**, where Li⁺ ions are reversibly inserted into host materials (e.g., graphite, LiCoO₂).
- The **rocking chair mechanism** describes Li⁺ ions shuttling between anode and cathode during charge/discharge.
- The lattice structure of the electrodes remains stable over a wide range of lithium content (high stoichiometry).
- No metallic lithium is deposited — this improves safety and cycle life.

---

## 2. 🔄 Charge Transport & Efficiency

- **Li⁺ ions** handle charge transport inside the cell.
- Electrons flow through the external circuit; ions flow through the electrolyte.
- **Coulombic efficiency**:  
  

\[
  \eta_{\text{coulombic}} = \frac{\text{charge out}}{\text{charge in}} \approx 100\%
  \]


- **Energy efficiency**:  
  

\[
  \eta_{\text{energy}} \approx 95\%
  \]



---

## 3. 📉 Voltage Behavior During Discharge

- Terminal voltage decreases with increasing discharge current due to **internal resistance**.
- At high current, voltage drops faster → apparent capacity is lower.
- **Cutoff voltage** is defined by manufacturers to prevent over-discharge:
  

\[
  V_{\text{cutoff}} \approx 2.5 - 3.0\, \text{V (Li-ion)},\quad 1.75\, \text{V (Lead-acid)}
  \]



---

## 4. 🧪 Aging Mechanisms in Lithium-Ion Cells

Lithium-ion cells degrade over time due to:

- **SEI growth**:  
  - Solid Electrolyte Interphase forms on the anode  
  - Consumes Li⁺ and increases resistance

- **Loss of lithium inventory**:  
  - Irreversible side reactions reduce available Li⁺

- **Electrolyte decomposition**:  
  - Loss of additives reduces ionic conductivity

- **Particle fracture**:  
  - Mechanical stress from volume changes breaks active material

- **Conduction loss**:  
  - Cracked particles lose electrical contact

- **Capacity fade**:  
  - Reduced ability to store charge over cycles

---

## 5. 🔋 Lead-Acid Battery Theory

- **Nominal voltage per cell**:  
  

\[
  U_N = 2.0\, \text{V}
  \]


  A 12 V battery consists of 6 cells.

- **Internal resistance (Ri)**:  
  Sum of:
  - Electrode resistance  
  - Connector resistance  
  - Electrolyte ion resistance  
  - Contact resistance

  Typical range:  
  

\[
  R_i \approx 5 - 30\, \text{m}\Omega
  \]


  Ri increases with:
  - Lower temperature  
  - Higher discharge depth

- **Gassing voltage**:  
  

\[
  V_{\text{gassing}} \approx 2.40 - 2.45\, \text{V per cell}
  \]


  Above this, water electrolysis occurs → H₂ and O₂ gas formation.

---

## 6. ⚠️ Summary of Aging Effects

| Aging Effect         | Cause                          | Impact                     |
|----------------------|--------------------------------|----------------------------|
| SEI Growth           | Electrolyte decomposition      | Increased resistance       |
| Lithium Loss         | Side reactions                 | Capacity fade              |
| Particle Fracture    | Volume change stress           | Conduction loss            |
| Additive Loss        | Electrolyte breakdown          | Reduced stability          |
| Gassing (Lead-acid)  | Overcharging                   | Water loss, safety risk    |

---

