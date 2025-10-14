
# EN3150 Assignment 03 – CNN for Image Classification

## 📌 Overview
This repository contains the implementation of **Assignment 03** for EN3150.  
The project focuses on building a **custom Convolutional Neural Network (CNN)** for image classification and comparing it with **transfer learning** using pretrained models such as ResNet and VGG.

---

## 👥 Team Members
- **THEJASVENAN T 220638J (Mechatronics)** – Team Lead, CNN architecture design, integration, documentation
- **ANANTHAKUMAR T. 220029T (Biomedical)** – Dataset selection, preprocessing, data pipeline
- **AHILAKUMARAN T. 220017F (ENTC)** – Training scripts, optimizer experiments, loss/accuracy plots
- **SAJEEVAN S. 220545V (Electrical)** – Evaluation metrics, transfer learning implementation, model comparison

---

## 📂 Repository Structure
```
EN3150_A03_CustomCNN_vs_TransferLearning/
│
├── data_preprocessing/        # Dataset loading, cleaning, splitting
│   └── data_preprocessing.py
│
├── models/                    # CNN + pretrained models
│   ├── cnn_model.py
│   └── transfer_learning.py
│
├── training/                  # Training scripts + optimizer experiments
│   ├── train_cnn.py
│   ├── optimizer_comparison.py
│   └── plots/                 # Loss/accuracy plots
│
├── evaluation/                # Evaluation metrics + confusion matrix
│   ├── evaluate.py
│   └── metrics_report.md
│
├── report/                    # Final report, references, figures
│   └── EN3150_A03_Report.pdf
│
├── README.md                  # Project overview, setup instructions
└── requirements.txt           # Dependencies
```

---

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Thejasvenan/EN3150_A03_Vision.git
   cd EN3150_A03_Vision
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run preprocessing:
   ```bash
   python data_preprocessing/data_preprocessing.py
   ```

4. Train the custom CNN:
   ```bash
   python training/train_cnn.py
   ```

5. Evaluate the model:
   ```bash
   python evaluation/evaluate.py
   ```

---

## 📊 Deliverables
- Custom CNN implementation and results
- Transfer learning implementation and results
- Comparison of models (accuracy, precision, recall, confusion matrix)
- Final report with discussion and analysis

---

## 📅 Contribution Plan
- **Week 1**: Dataset selection + preprocessing (B), CNN architecture setup (A), Training + optimizer experiments (C), evaluation metrics (D)  
- **Week 2**: Transfer learning implementation (D), documentation & plots (C), Report writing (all), final integration (A)

---

## 📜 License
This project is for academic purposes (EN3150). All rights reserved by the authors.
```
