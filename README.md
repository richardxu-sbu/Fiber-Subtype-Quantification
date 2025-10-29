# Fiber-Subtype-Quantification
Automated classification of muscle fibers (GFP/RFP) using Python &amp; skimage

# Automated Muscle Fiber Classification (GFP/RFP)

This repository contains a Python-based pipeline for automated quantification and classification of muscle fiber subtypes from immunofluorescence images (e.g., GFP, RFP, Laminin).  
The analysis was developed during my research at Stony Brook University (Pisconti Lab) to replace manual counting under the microscope.

---

## 🧠 Features
- Image segmentation of individual fibers using watershed algorithm  
- Fluorescence-based subtype classification (GFP+, RFP+, double+, negative)  
- Automated visualization of classified fibers  
- Fully executable on Google Colab (no installation needed)

---

## 🚀 Usage
1. Upload your **laminin**, **GFP**, and **RFP** images.
2. Run the notebook step by step on **Google Colab**.
3. The output will display:
   - Fiber segmentation results  
   - Positive/negative classification  
   - Per-class visualization

---

## 🧩 Dependencies
Python ≥ 3.9  

---

---

## 🧩 Authors

- **Ruixin (Richard) Xu** — Stony Brook University, Department of Pathology  
- **Xuejian Huang** — University at Buffalo, Department of Pharmacology and Toxicology  

---

## 🧠 Acknowledgements

This project, *Fiber Subtype Quantification*, was developed by Ruixin Xu and Xuejian Huang  
under the supervision of **Dr. Dada Pisconti** (Department of Biochemistry & Cell Biology, Stony Brook University).  

We sincerely thank Dr. Pisconti for her data, mentorship, guidance, and support  
throughout the development of this work.

---

## 📚 Citation

If you use or adapt this code in your research, please cite or acknowledge this repository:

> Xu, R., & Huang, X. (2025). *Fiber Subtype Quantification (Python Pipeline)*.  
> Pisconti Laboratory, Department of Biochemistry & Cell Biology, Stony Brook University.  
> GitHub Repository: [https://github.com/richardxu-sbu/Fiber-Subtype-Quantification](https://github.com/richardxu-sbu/Fiber-Subtype-Quantification)

---

## 🪪 License

This project is distributed under the [MIT License](./LICENSE).  
You are free to use, modify, and distribute the code, provided that proper credit is given  
to the authors and supervisors listed above.

---
