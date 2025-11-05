# Spoofing Android GNSS Measurements

This project analyzes **Android raw GNSS measurements** to evaluate positioning accuracy and vulnerabilities under different scenarios, including **spoofing attacks**.

---

## 🛰️ Overview
Experiments were conducted using an **Honor 200 Lite (Android 14)** and the **GNSS Logger** app.  
Data were processed in **MATLAB** to analyze pseudoranges, Doppler rates, C/N₀, and PVT performance.

---

## 🔬 Tested Scenarios
- **Open-sky** – Baseline reference  
- **Power-saving mode** – Reduced accuracy  
- **Indoor & Microwave** – Multipath and signal blocking  
- **Position Spoofing** – Artificial location shift (~1 km)  
- **Spoofing with Delay** – Time delay (5 ms) affecting clock bias

---

## 📈 Key Findings
- Stable open-sky performance (≈ 17 m error)  
- Indoor and microwave severely degrade accuracy  
- Spoofing alters position and timing with minimal change in signal strength  
- PRR–pseudorange mismatch helps detect spoofing

---

## ⚙️ Tools
- **Device:** Honor 200 Lite  
- **Software:** GNSS Logger, MATLAB  
- **Files:** `.txt` raw logs, MATLAB scripts, generated figures

---

**Author:** Antonello Di Pede – GNSS Lab, Politecnico di Torino (2025)
