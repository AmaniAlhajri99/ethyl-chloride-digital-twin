# 🧪 Ethyl Chloride Plant: AI Digital Twin & Process Optimization

[![Domain](https://img.shields.io/badge/Domain-Chemical%20Engineering-blue.svg)](https://github.com/)
[![Industry 4.0](https://img.shields.io/badge/Framework-Industry%204.0%20Digital%20Twin-orange.svg)](https://github.com/)
[![Tech Stack](https://img.shields.io/badge/Stack-Python%20%7C%20SciPy%20%7C%20Scikit--Learn-green.svg)](https://github.com/)
[![Status](https://img.shields.io/badge/Status-Production%20Optimized-success.svg)](https://github.com/)

---

## 📌 Project Origin & Vision
This project originated as an academic **University Capstone Design Project** for an industrial Ethyl Chloride production plant. To bridge the gap between classical plant design and the future of smart manufacturing, this work was independently evolved into an **Industry 4.0 AI Digital Twin**. By combining rigorous chemical engineering thermodynamics with machine learning surrogate modeling and numerical optimization, the system successfully unlocks hidden plant capacity with **Zero OPEX Penalty**.

---

## 📊 Key Performance Metrics

| Operational Metric | Baseline Design | AI-Optimized State | Improvement / Status |
| :--- | :---: | :---: | :---: |
| **Ethyl Chloride Production Rate** | $1,514.92 \text{ kg/hr}$ | **$1,575.36 \text{ kg/hr}$** | **+4.0% Yield Increase** 🚀 |
| **Reactor Temperature ($T$)** | $190.00 \text{ °C}$ | **$193.81 \text{ °C}$** | Thermal Sweet Spot |
| **Operating Cost Penalty (OPEX)** | Baseline Cost | **Zero Penalty** | Maintained via Heat Integration |
| **Capital Expenditure (CAPEX)** | New Equipment | **Zero CAPEX** | Utilized Existing Asset Margins |

---

## ⚙️ Chemical Engineering Scope & Fundamentals

The process centers on the vapor-phase hydrochlorination of ethylene/hydrochloric acid or direct chlorination pathways. Key engineering concepts evaluated include:
* **Reactor Kinetics & Stoichiometry:** Balancing feed ratios to maximize single-pass conversion while managing exothermic heat release.
* **Vapor-Liquid Equilibrium (VLE):** Rigorous multi-component flash calculations for separation units.
* **Pinch Analysis & Heat Integration:** Utilizing feed-effluent heat exchangers (H-1) to recover reaction heat and minimize external utility duties.
* **Fractionation Column Optimization:** Tuning column pressure and reflux ratios to maximize product purity ($>99.5\%$) without overloading condenser refrigeration loads.

---

## 🤖 AI & Technical Implementation Stack

1. **Surrogate Modeling:** A **Random Forest Regressor** trained on plant simulation datasets to map non-linear thermodynamic and kinetic responses instantly.
2. **Numerical Optimization:** Implemented the **SciPy Nelder-Mead optimization algorithm** to solve constrained economic objective functions.
3. **Economic Profit Objective Function:**
   $$\text{Max } \Pi = (\text{Value of } \text{C}_2\text{H}_5\text{Cl Output}) - (\text{Raw Material Costs}) - (\text{Compression \& Utility OPEX})$$

---

## 📂 Repository Structure

```text
ethyl-chloride-digital-twin/
│
├── README.md                          # Project documentation
├── src/
│   ├── process_simulation.py          # Core mass & energy balance models
│   ├── surrogate_model.py             # Random Forest ML predictor
│   └── optimizer.py                   # SciPy Nelder-Mead optimization script
├── docs/
│   └── ethyl_chloride_optimization_report.pdf  # Full 2-page engineering report
└── assets/
    ├── pfd_diagram.png                # Process Flow Diagram
    └── 3d_plant_layout.png            # Optimized 3D Plant Design
