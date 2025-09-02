# 🏗️ ASIC Physical Design Flow – From RTL to GDSII  

Hi 👋, I’m **Harshan Kumar** – a passionate **Physical Design Engineer**.  
This repository documents my end-to-end **ASIC Physical Design Flow** project implemented using **Synopsys EDA tools** (Design Compiler, ICC2, PrimeTime).  

---

## 🚀 Project Overview  
- **Objective**: Implement a complete PD flow starting from **RTL → Synthesis → Floorplanning → Placement → CTS → Routing → Timing Analysis → GDSII**.  
- **Design**: ChipTop module with ~61K standard cells, 40 macros, and 4 clock domain.  
- **Target Frequency**: **416.7 MHz** (2.4 ns clock period).  
- **Flow Steps**:
  1. RTL Synthesis (**Design Compiler**)  
  2. Floorplanning (**ICC2**)  
  3. Placement & Optimization (**ICC2**)  
  4. Clock Tree Synthesis (CTS)  
  5. Routing (Global + Detail)  
  6. Static Timing Analysis (**PrimeTime**)  
  7. GDSII Generation  

---

## 📊 Key Results  
- **Utilization**: 73%  
- **Hold WNS**: -0.04 ns  
- **Clock Period**: 2.4ns (416.7 MHz)  
- **Final Output**: DRC/LVS clean **GDSII layout**  

📌 *Highlights:*  
- Achieved timing closure with **no violations**  
- Optimized area & congestion  
- Power, timing, and DRC reports included  

---

## 🛠️ Tools Used  
- **Synthesis** → Synopsys Design Compiler  
- **Place & Route** → Synopsys ICC2  
- **Timing Analysis** → Synopsys PrimeTime  


---

## 📄 License  
This project is licensed under the **MIT License**.  

---

![Status](https://img.shields.io/badge/Project-PD%20Flow-blue)
![Tools](https://img.shields.io/badge/Tools-DC%20%7C%20ICC2%20%7C%20PrimeTime-green)
![Macros](https://img.shields.io/badge/Macros-40-lightgrey)
![Std Cells](https://img.shields.io/badge/Std%20Cells-61K-blue)
![Frequency](https://img.shields.io/badge/Frequency-416.7MHz-red)
![Utilization](https://img.shields.io/badge/Utilization-73%25-orange)
![Timing](https://img.shields.io/badge/Hold%20WNS---0.04ns-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

⭐ **If you find this project useful, consider giving it a star!**
