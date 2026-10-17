# variable-star-analysis

Computational tools for modeling stellar variability, phase-folded light curves, and physical parameter estimation of pulsating variables.

---

## 🔬 Scientific Objective
This repository provides a rigorous algorithmic pipeline for time-series photometry and frequency analysis of variable stars. By processing raw observational light curves (such as FITS data or ASCII time-series formats), the framework automates period determination, phase-folding, and variability characterization to assist in stellar pulsation research.

---

## 🚀 Key Features
* **Time-Series Photometry Handling:** Ingestion and preprocessing of stellar flux and magnitude measurements.
* **Frequency Extraction:** Implementation of Lomb-Scargle periodograms to identify dominant pulsation frequencies and amplitudes.
* **Phase-Folding Utilities:** Transformation of observational time vectors into orbital or pulsation phase domains.
* **Astrophysical Modeling:** Diagnostic scripts for estimating physical parameters of variable stellar systems.

---

## 🛠️ Tech Stack & Dependencies
Built with Python 3.x, relying on core scientific and astronomical computing libraries:
* `numpy` & `scipy` — Numerical computation and statistical analysis
* `astropy` — Handling FITS files, time standards, and astronomical units
* `matplotlib` — Publication-grade plotting of light curves and periodograms

---

## 📦 Installation
Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/Kavya-Phy/variable-star-analysis.git](https://github.com/Kavya-Phy/variable-star-analysis.git)
cd variable-star-analysis
pip install -r requirements.txt
