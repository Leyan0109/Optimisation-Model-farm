# 🐄 Bowman Farm Optimisation Model (2025–2026)

## 🔍 Project Overview

This project presents a **stochastic integer linear programming (ILP) optimisation model** developed in **Python (PuLP)** to help a farm (the Bowman family) make optimal operational decisions. The goal is to **maximize expected farm wealth** over a one-year planning horizon, under uncertain **weather-dependent crop yields and labour requirements**.

Key decisions include:

* Livestock purchases and sales (cows & hens)
* Crop allocation (corn, wheat, rapeseed)
* Feed requirements and crop storage
* Financial investment for interest gains

The model helps allocate limited land, labour, and financial resources for **profit maximization**, while accounting for risk and resource constraints.

---

## 💡 Key Findings

* The **optimal strategy** recommends **investing heavily in hens** and **rapeseed cultivation**, with minimal cow investment.
* **1600 hens** are purchased while **400 are sold**, maximizing income under uncertain weather.
* **778 acres** are planted with **rapeseed**, leveraging its high profitability.
* A total **expected wealth of £1,288,507.28** is achieved under the most likely weather scenario (Frost & Dry).
* The model prioritizes **feed sufficiency** and **financial sustainability** through strategic crop storage and investment.

## 🧰 Tech Stack & Tools

* **Language**: Python 3.x
* **Library**: [`PuLP`](https://coin-or.github.io/pulp/) for optimisation
* **IDE**: Jupyter Notebook / VS Code
* **Visuals**: Matplotlib, Seaborn (optional for plotting)
* **GenAI**: ChatGPT for model formulation, code structure, and documentation support

---

## 📦 Repository Structure

```
bowman-farm-optimisation/
1. models/              # Python scripts for ILP model (PuLP)
2. analysis report/            # Parametric analysis results and graphs
3. README.md            # Project documentation (this file)
```

---

## 📊 Parametric Analysis

To test model **robustness**, cow purchase prices and income levels were varied. Key insights:

* Even with increased cow income, **hens remained the preferred livestock** due to higher return on investment.
* **Model results remained stable** across most price ranges, showing strong decision robustness.
* GenAI helped structure this analysis using **nested loops** and **clear visual strategies** (e.g., 2D heatmaps).

---

## 📌 Conclusion

This project showcases real-world application of:

* **Operations Research**
* **Mathematical Optimisation**
* **Decision Support Systems**
* **Data-Driven Agricultural Planning**

It reflects strong analytical thinking, programming, and the ability to integrate advanced tools (like GenAI) into practical problem-solving workflows.
