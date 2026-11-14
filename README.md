# Patch Array Biosensing of Glucose in Aqueous Phantoms

This repository contains the underlying data, simulation exports, and measurement files for the manuscript **"Patch Array Biosensing of Glucose in Aqueous Phantoms"**.

## Authors
Disha Daniel, Abdulla M Ali, Sahithi Ganti, A Harsha Kumar, Upender P.  
*Vellore Institute of Technology, Chennai, Tamil Nadu, India*

## Overview
This repository provides the open-access datasets required to reproduce the graphs and evaluate the two-by-two microstrip patch antenna array presented in the study. It includes the exported CST Studio Suite simulation data, Vector Network Analyzer (VNA) hardware measurements, and relevant imagery.

## Repository Structure
* **`csv/`**: Contains the raw data files exported from the CST Studio Suite simulations (parametric sweeps, normal/hyperglycemic phantom responses) and the Keysight N9918A VNA hardware measurements (unloaded and on-body $S_{11}$ parameters, VSWR).
* **`images/`**: Contains the electric field and surface current density distributions, hardware prototype photographs, and original plot images used in the manuscript.

## Usage
The provided `.csv` files contain the frequency and magnitude data points. They can be directly imported into Python, MATLAB, or Excel to recreate the reflection coefficient ($S_{11}$) and parametric study plots discussed in the paper.