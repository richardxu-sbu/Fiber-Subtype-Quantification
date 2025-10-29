# fiber-subtype-quantification
Automated classification of muscle fibers (GFP/RFP) using Python &amp; skimage


This program is written by myself and ChatGPT (THIS IS NOT A PERFECT PROGRAM, STILL UPDATING)
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
