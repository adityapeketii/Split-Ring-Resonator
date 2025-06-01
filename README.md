# 📡 Design and Analysis of Split Ring Resonator Structures (S25 RF Sensor Design Project)


## 📘 Overview

This project explores the **design, simulation, and performance analysis** of **Split Ring Resonators (SRRs)** using HFSS, focusing on both square and circular geometries. These structures serve as compact, tunable, and high-sensitivity components in **RF sensing** and **filtering applications**.

---

## 👥 Team Members

- **Aasrith Reddy Vedanaparti** — 2023102031  
- **Aditya Peketi** — 2024122001  
- **Akshat Puneet** — 2024122005  
- **Hrishikesh Milind Gawas** — 2024122006  
- **Vignesh Vembar Manikantan** — 2023102019  

---

## 🎯 Objective

Design an SRR-based **notch filter** with:

- **Target Resonant Frequency**: 2.5 GHz  
- **Compact Design**  
- **High Sensitivity (>10%)**  
- **Excellent Filtering (S21 < -10 dB at resonance)**

---

## 🛠️ Tools Used

- **ANSYS HFSS** for full-wave electromagnetic simulation
- **FR04-Epoxy** as substrate (εr = 4.4)

---

## 🧪 Results

### Square SRR (2 Rings)
- **fo** = 2.375 GHz  
- **S11** = -1.6671 dB  
- **S21** = -12.3756 dB

### Circular SRR
| Configuration | Resonant Frequency (GHz) | S11 (dB)     | S21 (dB)     |
|---------------|--------------------------|--------------|--------------|
| 2 Rings       | 2.85                     | -25.2810     | -0.7763      |
| 3 Rings       | 2.59                     | -22.9668     | -0.9142      |
| 4 Rings       | 2.53                     | -22.2139     | -0.9803      |

---

## ✅ Summary

- **Resonance Tuning**: Achieved via ring count and geometry adjustments.
- **High Selectivity**: Demonstrated through S11/S21 and Q-factor.
- **Application Scope**: Wireless sensing, material characterization, RF filters.

---

## 📚 References

- [IEEE - Design and Analysis of a Meta Material based Nested Circular SRR](https://doi.org/10.1109/ICACRS55517.2022.10029069)
- [IEEE - Comparative Analysis of SRRs of Different Geometries](https://doi.org/10.1109/AEMC.2011.6256871)
- [SRR-based Filters for GSM and ISM Bands](https://dergipark.org.tr/en/download/article-file/1034899)

---

> 📍 *Developed as part of the course on Radio Frequency Based Sensors at the International Institute of Information Technology, Hyderabad.*
