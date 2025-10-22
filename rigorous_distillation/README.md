# 🧪 Multicomponent Rigorous Distillation in DWSIM

This repository documents a simulation project based on the [YouTube tuotiral by EduX](https://www.youtube.com/watch?v=U9JQXqgsx4s), where I modeled a multicomponent hydrocarbon distillation column using DWSIM's rigorous distillation framework.

## 🎯 Objective

To simulate the separation of propane, isobutane, neopentane, and n-heptane using a 14-stage distillation column, and analyze vapor-liquid distribution and volatility behavior across stages.

## 🛠️ Tools & Setup

- **Software:** DWSIM v7.5+
- **Thermodynamic Model:** Peng-Robinson (PR)
- **Column Configuration:**
  - 14 stages (including condenser and reboiler)
  - Overhead pressure: 1.776 atm
  - Column pressure drop: 0.2 atm
  - Solver: Wang-Henke (Bubble Point)
- **Feed Composition:**
  - Propane, Isobutane, Neopentane, n-Heptane
  - Molar flow: 5000 kmol/h
  - Temperature: ~45°C
  - Vapor fraction: 0

## 📊 Results

![DWSIM Simulation](https://github.com/Subtlr/dwsim_projects/blob/main/rigorous_distillation/images/the%20thing.png)

Three key plots were generated to visualize component behavior:

### 1. Vapor Flow Rates vs Stage
Shows how each hydrocarbon distributes in the vapor phase across the column.

### 2. Liquid Flow Rates vs Stage
Highlights the accumulation and depletion of components in the liquid phase.

### 3. K-values vs Stage
Illustrates relative volatility and separation efficiency for each compound.

![Vapor Flow Graph](https://github.com/Subtlr/dwsim_projects/blob/main/rigorous_distillation/images/download.png)

## 🧠 Author

**Subert**  
First-year Chemical Engineering student at UNDIP  

## 🔗 Connect

- [LinkedIn](https://www.linkedin.com/in/fadly-nabil-liantama-550284371/)
- [GitHub](https://github.com/Subtlr)

## Considerations
This readme file was made with the assistance of a Large Language Model (LLM)

---

