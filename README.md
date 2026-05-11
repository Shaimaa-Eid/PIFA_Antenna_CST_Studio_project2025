## 📡 Project Overview
This repository contains the design, simulation, and optimization of a compact **Planar Inverted-F Antenna (PIFA)** for mobile applications. The simulation and parameter sweeping were performed using **CST Microwave Studio**.

## 📐 Design Specifications
* **Antenna Type:** Planar Inverted-F Antenna (PIFA)
* **Feeding Method:** Coaxial Probe Feed
* **Miniaturization Technique:** Using a Shorting Pin to achieve quarter-wavelength ($\lambda/4$) resonance.
* **Operating Frequencies:** Dual-Band operation (e.g., 2.45 GHz & 2.65 GHz) achieved via surface slots.

## 📊 Key Results & Simulation
### 1. 3D Antenna Model
*The structural design includes the radiating patch, shorting pin, and coaxial feed.*

![3D Model](3D%20model.png)

### 2. Return Loss (S-Parameters)
*Parameter sweep optimization (`xfeed`) was performed to achieve impedance matching. The optimal S11 curve shows deep resonances below -10 dB.*

![S11 Graph](S11%20curve.png)

### 3. Radiation Pattern (Far-field)
*The antenna exhibits a low-directivity (approx. 2.5 dBi), omnidirectional radiation pattern, which is ideal for mobile handset connectivity.*

![Radiation Pattern](radation%20pattern.png)
## 🛠️ Tools Used
* CST Studio Suite
