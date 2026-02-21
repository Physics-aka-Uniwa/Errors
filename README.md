<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
</p>

---

<p align="center">
  <strong>Physics</strong>
</p>

<h1 align="center">
  Errors
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<hr/>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Dimitrios Nikolopoulos, Professor
</p>
<p align="center">
  <a href="https://idpe.uniwa.gr/en/nikolopoulos" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/dimitrios-nikolopoulos-bb793895/" target="_blank">LinkedIn</a>
</p>

</hr>

---

<p align="center">
  Athens, December 2019
</p>

---

<p align="center">
  <img src="https://i.ytimg.com/vi/FIRTZbfDhtY/sddefault.jpg" width="250"/>
</p>

---

# README

## Errors

This repository summarizes the physics project completed by **Vasileios Evangelos Athanasiou** for the University of West Attica. The project focuses on **statistical error analysis**, **significant figures**, and the **least squares method** applied to physical measurements.

---

## Table of Contents

| Section | Folder/File          | Description                                |
| ------: | -------------------- | ------------------------------------------ |
|       1 | `docs/`              | Documentation related to error analysis    |
|     1.1 | `docs/Errors.pdf`    | Error analysis document (English)          |
|     1.2 | `docs/Σφάλματα.pdf`  | Error analysis document (Greek)            |
|       2 | `tables/`            | Tables and datasets used in analysis       |
|     2.1 | `tables/Tables.xlsx` | Error-related tables in spreadsheet format |
|     2.2 | `tables/Πίνακες.pdf` | Error-related tables in PDF format         |
|       3 | `README.md`          | Repository overview and usage instructions |

---

## 1. Project Objectives

### 1.1 Significant Figures and Rounding

The project begins by identifying significant figures and performing rounding operations.

- **Identification:** Determining the number of significant figures (e.g., 976.45 → 5 significant figures).
- **Rounding:** Converting values to a defined number of significant figures (e.g., 8.314 → 8.3).

---

## 2. Statistical Analysis of Measurements

Experimental datasets are analyzed to compute statistical properties of measurements.

- **Mean Value Calculation**

$$
\bar{x} = \frac{1}{n}\sum x_i
$$

- **Standard Deviation of the Mean**

$$
\sigma(\bar{x}) = \sqrt{\frac{\sum(\Delta x_i)^2}{n(n-1)}}
$$

- **Result Formatting**

Final measurements are expressed with uncertainties, e.g.:

$$
(56.7 \pm 0.1)\,\text{cm}
$$

---

## 3. Area Calculation and Error Propagation

The area of a rectangle is computed from measured dimensions with uncertainty propagation.

- **Area Calculation**

$$
\bar{A} = \bar{x} \times \bar{y}
$$

- **Error Propagation**

Total uncertainty is derived from uncertainties of both dimensions.

---

## 4. Least Squares Method (Linear Regression)

The least squares method is applied to experimental measurements to determine physical constants.

### 4.1 Pendulum Motion

Analyzes the relation between oscillation period \(T_i\) and pendulum length \(x_i\) to determine:

- Gravity acceleration \(g\)
- Experimental constant \(a\)

### 4.2 Mass–Spring System

Uses oscillation periods \(T_i\) for varying masses \(m_i\) to compute:

- Spring constant \(D\)
- Effective mass of the spring \(m\_{ελ}\)

---

## 5. Summary of Calculated Constants

Based on experimental data:

- **Gravity acceleration (g):** 0.92145 cm²/s
- **Spring Constant (D):** 0.40807 N/m
- **Calculated Area (A):** 980.2 cm² ± 1.0%

---

## 6. Conclusion

The project demonstrates practical application of statistical methods, uncertainty analysis, and regression techniques in physics experiments, reinforcing foundational measurement and analysis skills.
