# Solar Cell Quality Inspection using AI  
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green">
  <img src="https://img.shields.io/badge/Computer%20Vision-OpenCV-orange">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen">
</p>


A lightweight **AI framework** for detecting **faults in photovoltaic (PV) cells** using **Electroluminescence (EL) imaging** and **Random Forest Classifier**.  
Designed for **resource-constrained environments**, this project provides a cost-effective solution for solar panel defect detection and quality inspection.  

---

## Features
✨ Automated preprocessing of EL images (resize, flatten, label cleaning)  
✨ Lightweight Random Forest model (no GPU required)  
✨ 5-fold cross-validation for robust evaluation  
✨ Confusion matrix and tabular performance summaries  
✨ Reproducible pipeline for academic and industrial use  

---

## Performance
| Metric       | Score   |
|--------------|---------|
| **Accuracy** | 83.5%   |
| **Precision**| 80.9%   |
| **Recall**   | 75.3%   |
| **F1-score** | 77.3%   |

---

## Tech Stack
- **Programming:** Python  
- **Libraries:** OpenCV, Pandas, NumPy, Scikit-learn, Matplotlib  
- **Dataset:** [ELPV Dataset](https://paperswithcode.com/dataset/elpv)  

---

## Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/PV-Defect-Detection.git
cd PV-Defect-Detection
```
### 2️⃣ Install dependencies
```
pip install -r requirements.txt
```
### 3️⃣ Run the Jupyter Notebook
```
jupyter notebook
```
---

### Project Structure
```
PV-Defect-Detection/
│── data/                # Dataset folder (images + labels.csv)
│── Solar_Cell_Fault_Detection.ipynb   # Main notebook
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```
