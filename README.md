# BIPV_Improvement
"Optimization of BIPV and PV Array Efficiency Under Partial Shading Conditions Using Fuzzy Logic and Perturb and Observe Method"

# Performance Improvement of BIPV Systems Using Modified P&O with Fuzzy Logic Under Partial Shading

This repository contains the MATLAB/Simulink models, scripts, and documentation for the project focused on enhancing the energy output of BIPV (Building-Integrated Photovoltaic) systems under dynamic partial shading using an improved MPPT technique.

## 📌 Overview

The project implements a **Modified Perturb and Observe (P&O)** algorithm integrated with a **Fuzzy Logic Controller** to effectively track the Global Maximum Power Point (GMPP) in non-uniform irradiance conditions typical in urban BIPV environments.

## 🛠️ Tools & Technologies

- MATLAB / Simulink
- MPPT Algorithm: Modified P&O
- Fuzzy Logic Toolbox
- BIPV Array Modeling
- Dynamic Shading Profiles

## 🧠 Objectives

- To overcome the limitations of conventional P&O in tracking GMPP under partial shading.
- To apply Fuzzy Logic for adaptive step size and intelligent decision making.
- To improve energy harvesting efficiency and reduce tracking errors.

## 📂 Project Structure

├── BIPV_Modified_PO_Fuzzy.slx # Simulink model with fuzzy logic and modified P&O
├── fuzzy_controller_design.fis # Fuzzy Inference System file
├── plot_results.m # Scripts for result analysis
├── report.pdf # Final report
├── presentation.pptx # Project presentation
└── README.md # This file


## ⚙️ Methodology

- A BIPV model was created in MATLAB/Simulink with partial shading applied via time-varying irradiance blocks.
- The P&O algorithm was modified to include dynamic step-size adjustment.
- A Fuzzy Logic Controller was designed to enhance MPPT response under rapidly changing shading conditions.
- Performance was compared with conventional P&O in terms of efficiency, ripple, and convergence speed.

## 📈 Key Results

- **Faster convergence** to GMPP under variable shading.
- **Higher tracking accuracy** and reduced oscillations at steady-state.
- **Improved overall energy harvest** compared to conventional MPPT approaches.

## 📜 License

This project is for academic and educational use only. Please cite or acknowledge the work appropriately if used.


