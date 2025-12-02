# Adaptive-BIPV-Optimization

This repository contains the Python implementation developed for optimizing adaptive BIPV (Building-Integrated Photovoltaic) shading systems using state-of-the-art multi-objective metaheuristic algorithms, including:

- **MOGWO** – Multi-Objective Grey Wolf Optimizer  
- **MOWOA** – Multi-Objective Whale Optimization Algorithm  
- **MOACO** – Multi-Objective Ant Colony Optimization  
- **MOMFO** – Multi-Objective Moth Flame Optimization  

The objective of this work is to maximize **PV energy generation** while enhancing **indoor comfort**, enabling architects and energy designers to evaluate dynamic shading strategies for BIPV facades under real operating conditions.

---

## 📘 Background

This code was originally developed as part of my research work (2023–2024), during the preparation of an academic article focused on adaptive photovoltaic building envelopes.  
The study combines:

- Dynamic shading control  
- Solar irradiance modeling  
- Metaheuristic optimization  
- BIPV system performance evaluation  

This repository was cleaned, organized, and uploaded to GitHub in **2025** exclusively for documentation and long-term preservation.

---

## 🧠 Methodolog
The workflow implemented in this project follows:

1. **Input data preparation**  
   - Climate data (EPW / measured data)  
   - Building orientation and geometry  
   - PV panel characteristics  

2. **Simulation of BIPV shading states**  
   - Evaluation of shading angles  
   - Irradiance and energy generation modeling  
   - Integration with comfort metrics  

3. **Optimization process**  
   - Selection of multi-objective algorithm  
   - Fitness evaluation (Energy vs Comfort)  
   - Pareto front generation  

4. **Result extraction & visualization**  
   - Best solution identification  
   - Multi-objective trade-off analysis
