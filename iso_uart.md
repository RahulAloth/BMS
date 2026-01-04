# 🔌 Infineon iso UART — Isolated Communication for High‑Voltage Battery Systems  
*A complete study note combining protocol fundamentals, operation, topology, and BMS integration*

---

# 📘 1. What Infineon iso UART Actually Is

**iso UART** (isolated UART) is Infineon’s communication protocol designed for **robust, high‑voltage‑safe communication** between domains such as:

- High‑voltage battery cells ↔ low‑voltage controller  
- Motor inverter ↔ control MCU  
- BMS ICs connected in a daisy chain  

Infineon describes it as:

> “An isolated Universal Asynchronous Receiver‑Transmitter communication protocol… enabling robust and isolated communication, especially between high‑ and low‑voltage domains.”

It is widely used in Infineon’s BMS ecosystem, including the **TLE9015QU** BMS transceiver.

---

# ⭐ 2. Where iso UART Is Used

### 🔹 In Battery Management Systems (BMS)
- Communication between **cell monitoring ICs (CMICs)**  
- Communication between **pack monitor** and **cell monitors**  
- Daisy‑chain networks inside HV battery packs  

### 🔹 In Motor Control
- Inverter ↔ control MCU communication  

### 🔹 In High‑Voltage Systems
- Safe communication across isolation barriers  
- Noise‑immune signaling in harsh automotive environments  

---

# 🧩 3. Key Features of Infineon iso UART

- **Isolated UART communication**  
- **Differential, current‑edge‑triggered physical layer**  
- **2 Mbit/s data rate**  
- **Two‑wire, half‑duplex**  
- **Supports daisy‑chain networks**  
- **Robust against EMI and HV noise**  
- **Allows synchronous voltage + current measurement**  
- **Supports impedance measurement (EIS)**  

Used in Infineon’s **TLE9015QU**, which provides:

- Two iso UART interfaces  
- Built‑in isolation  
- Daisy‑chain routing  
- High‑voltage robustness  

---

# 🔋 4. How iso UART Fits Into PSOC™ HVPA‑SPM 1.0 Applications

In a typical battery pack:

[Cell Balancers] → Monitor each cell
[PSOC HVPA-SPM 1.0] → Measures pack current + voltage
[Host Controller] → Supervises entire battery system


The iso UART interface connects:

Cell Monitoring ICs (slaves)
↓
Pack Monitor (PSOC HVPA-SPM 1.0)
↓
Host Controller (Master ECU)


This enables:

- Safe communication across HV domains  
- Daisy‑chain messaging  
- Synchronous measurement for impedance analysis  

---

# 🧠 5. Overview of iso UART Interface

iso UART is a **point‑to‑point**, **differential**, **current‑edge‑triggered** UART interface.

### Physical Layer Characteristics

• Two-wire differential signaling
• Half-duplex communication
• Current-edge triggered (not voltage-level triggered)
• Isolation capacitors used for signal transfer


This makes it extremely robust in noisy HV environments.

---

# 📡 6. Protocol Basics

### 🔹 Two‑Wire Differential Signaling

Line+ and Line− carry differential current pulses


### 🔹 Half‑Duplex


Only one device transmits at a time


### 🔹 Current‑Edge Triggering
Logic is encoded in **edges**, not voltage levels.

### Logic Encoding


ISO UTH 1 Edge → Logic 1
ISO UTH 0 Edge → Logic 0


### Signal Flow

Transmitter → Square wave
Isolation capacitor → Converts to edge pattern
Receiver → Reconstructs digital bits


---

# 🔍 7. Measurement Capabilities Enabled by iso UART

iso UART allows **synchronous measurement** across the daisy chain:

### 🔹 Synchronous Cell Voltage Measurement  
All cell monitors sample at the same instant.

### 🔹 Synchronous Current Measurement  
Pack current (from PSOC HVPA‑SPM 1.0) is sampled simultaneously.

### 🔹 Impedance Measurement (EIS)
Because voltage + current are sampled together:



Impedance = Voltage Response / Current Excitation


This enables:

- Cell impedance tracking  
- Aging analysis  
- Fault detection  

---

# ⚙️ 8. Operation Principles of iso UART

### Step‑by‑Step

1. **Transmitter generates square wave**  
2. **Isolation capacitor** converts it into a pulse pattern  
3. **Receiver detects edges**  
4. **Threshold logic** determines 1 or 0  
5. **Message forwarded** to next device in chain  

### ASCII Diagram



TX Square Wave → || Isolation Cap || → Edge Pattern → RX Logic


---

# 🧱 9. iso UART Network Topologies

An iso UART network consists of:

- **One host (master)**  
- **Multiple nodes (slaves)**  
- Each node has a **unique NODE ID**  

Infineon supports three configurations:

---

## 1) Master on Top



Master
↓
Node 1
↓
Node 2
↓
Node 3


---

## 2) Master on Bottom



Node 3
↑
Node 2
↑
Node 1
↑
Master


Used when sensors send data upward and responses flow downward.

---

## 3) Ring Topology



Master → Node 1 → Node 2 → Node 3 → Master


Benefits:

- Redundancy  
- Fault tolerance  
- Higher reliability  

---

# 🔗 10. Daisy‑Chain Communication

iso UART supports daisy‑chain routing:

Master → Node 1 → Node 2 → Node 3 → ...


Each device:

- Forwards messages to the next  
- Adds its NODE ID  
- Responds only when addressed  

This ensures:

- Minimal wiring  
- High reliability  
- Safe HV communication  

---

# 🏁 11. Summary

iso UART is Infineon’s **isolated, differential, edge‑triggered UART protocol** designed for:

- High‑voltage battery systems  
- Daisy‑chain BMS communication  
- Safe HV ↔ LV domain communication  
- Synchronous measurement  
- Impedance analysis  

It is a key technology used in:

- **TLE9015QU** BMS transceivers  
- **PSOC™ HVPA‑SPM 1.0** pack monitors  
- Modern EV battery architectures  

Together, they enable **safe, robust, and scalable** communication inside high‑voltage battery packs.

---

OperationPrinciplesISOUART
iso_UART_Configurations
isoUART
DaisyChainConnections_iso_UART
HighlevelDiagram





