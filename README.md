# 🧮 y⁺ Calculator for CFD Grid Design

A lightweight and practical tool for CFD engineers to estimate **near-wall grid spacing**, **skin friction coefficient**, and **boundary-layer parameters** before mesh generation.  
This repository provides both an **executable tool** and a **technical LaTeX document** explaining all the formulas and their references.

The package can be downloaded with following link,
👉 [Download from Dropbox](https://www.dropbox.com/scl/fi/txnnfgsbe94b0qx5x57uo/yPlus_Calculator.zip?rlkey=w448jwiwaj08b3cnwomstbli3&st=a658q7da&dl=0)

---

## 🚀 Features

- **Executable Tool (`Calculate_yPlus.exe`)**
  - Computes:
    - Reynolds number  
    - Skin friction coefficient  
    - Boundary layer thickness  
    - First-layer grid spacing (`ΔS`)  
    - Number of prism layers (`N`)
  - Supports **cell-centered** and **vertex-centered** solvers.
  - Reads and writes data via `results.json` for easy integration into GUI tools or automated workflows.
  - Designed for users of **OpenFOAM**, **STAR-CCM+**, **Fluent**, and other CFD solvers.

- **Technical Documentation (`CFD_yPlus_Documentation.pdf`)**
  - Written in LaTeX.
  - Explains all calculation formulas and their physical meaning.
  - Includes:
    - Skin friction coefficient correlations  
      - Prandtl–Schlichting  
      - ITTC-1957  
      - Prandtl–Kármán  
    - Boundary-layer thickness estimation (Schlichting, White)
    - First grid spacing for cell-centered vs node-based solvers  
    - Prism layer count assuming a fixed stretching ratio (`r > 1.0`)

---

## 📘 References

1. White, Frank M. *Fluid Mechanics*, 7th ed. McGraw-Hill, 2011.  
2. Spurk, H. J. and Aksel, N. *Fluid Mechanics*. Springer Berlin Heidelberg, 2008.  
3. Jin, S., Zha, R., Peng, H., Qiu, W., and McTaggart, K., 2024.  
   *Determination of Maneuvering Force Coefficients for a Destroyer Model with OpenFOAM.*  
   *Journal of Ship Research*, 68(02), pp.39–65.  
4. Jin, S., Zha, R., Peng, H., Qiu, W., and Gospodnetic, S., 2020.  
   *2D CFD Studies on Effects of Leading-edge Propeller Manufacturing Defects on Cavitation Performance.*  
   *SNAME Maritime Convention (p. D033S015R003).*  
5. Jin, S., Peng, H., and Qiu, W., 2024.  
   *Numerical Study on Effects of Leading-edge Manufacturing Defects on Cavitation Performance of a Full-scale Propeller.*  
   *Physics of Fluids.*

---

## 🧰 Usage

## 📦 Download

The executable file (`Calculate_yPlus.exe`, 120 MB) is available here:

👉 [Download from Dropbox](https://www.dropbox.com/scl/fi/txnnfgsbe94b0qx5x57uo/yPlus_Calculator.zip?rlkey=w448jwiwaj08b3cnwomstbli3&st=a658q7da&dl=0)

