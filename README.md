# 🏗️ In-Situ Concrete Strength Predictor (ACI 228.1R Based)

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Field](https://img.shields.io/badge/Field-Civil%20Engineering-blue)
![Focus](https://img.shields.io/badge/Focus-Engineering%20Certainty-orange)

## 📌 Overview
This repository provides a **Plug-and-Play Jupyter Notebook** designed for Civil Engineers and Quality Control Managers to estimate in-situ concrete strength using Non-Destructive Testing (NDT) data, specifically following the concepts of **ACI 228.1R**.

Unlike standard estimation tools, this project focuses on **Engineering Certainty**. It doesn't just give you an average strength; it calculates the **Lower Confidence Limit (LCL)** to ensure structural safety and data reliability.

## 🚀 Key Features
- **Zero-Code Interface:** Designed for engineers with no prior programming experience.
- **Statistical Rigor:** Automatically calculates **RMSE** (Root Mean Square Error) and **R-Squared** to evaluate model accuracy.
- **Safety-First Logic:** Applies a statistical safety margin to provide a "Safe Design Strength" for site decisions.
- **Visual Reporting:** Generates high-quality charts for inclusion in professional engineering reports.

## 🛠️ How to Use
1. **Open** the `.ipynb` file in Google Colab or VS Code.
2. **Input Data:** Enter your NDT readings (e.g., UPV) and corresponding Core Strength results in Step 1.
3. **Run All:** The tool will automatically build the correlation and plot the safety curves.
4. **Predict:** Use the calculator cell to find the safe strength for any new site reading.

## ⚠️ Engineering Limitation
* **Data Pairing:** Requires a minimum of 6-10 data pairs (NDT + Core) for statistical validity per ACI 228.1R.
* **Site Specific:** The model developed for a specific mix design should not be blindly applied to different concrete mixes.

## 👨‍💻 Developed By
**Ali Abdulameer (Ali4Concrete)** *Computational Civil Engineer | Materials Data Analyst* Helping construction projects achieve engineering certainty via ASTM & Python.

---
**Disclaimer:** *This tool is for educational and preliminary estimation purposes. Always consult with a licensed structural engineer for critical site decisions.*
