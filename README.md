# Fabrication, Characterization, and Machine Learning–Based Optimization of Porous Aluminum

This repository contains the experimental dataset and Python codes used in the study titled:

**“Fabrication, Characterization, and Machine Learning–Based Optimization of Porous Aluminum Prepared with Sodium Chloride and Corn Flour as Dual Foaming Agents.”**

---

## 📘 Overview
This work investigates the fabrication of porous aluminum using **sodium chloride (NaCl)** and **corn flour** as dual foaming agents through a **powder metallurgy** process.  
The study explores how NaCl and corn flour influence **porosity**, **microstructure**, and **compressive strength**, and integrates **machine learning (Random Forest regression)** to predict and optimize process parameters for improved mechanical performance.

---

## 📂 Repository Contents
- **Porous Aluminum Data.xlsx** – Experimental dataset including:
  - Aluminum (%)
  - Sodium Chloride (%)
  - Corn Flour (%)
  - Porosity (%)
  - Compressive Strength (MPa)

- **porous_aluminum_optimization_parameter.py** – Python script implementing a Random Forest regression model for predicting and optimizing process parameters (Al, NaCl, Corn Flour, and Porosity) to maximize compressive strength.

- **porous_aluminum_plots.py** – Script for generating meaningful visualizations, including:
  - Experimental vs. ML-predicted trends of compressive strength  
  - Feature-importance ranking  
  - 3D surface plots of compressive strength vs. NaCl and porosity

---

## ⚙️ How to Run

 
You can run the entire workflow online without installing anything:  
https://colab.research.google.com/

1. Click the **“Open in Colab”** button above.  
2. Mount your GitHub repository in Colab (or upload the `.xlsx` file manually).  
3. Run all cells to reproduce model training, optimization, and visualizations.


