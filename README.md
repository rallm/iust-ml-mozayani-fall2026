# Machine Learning - Fall 2026

**Instructor:** Dr. Nasser Mozayani  
**Institution:** School of Computer Engineering, Iran University of Science and Technology (IUST)  
**Target Audience:** Graduate Engineering Students  

This repository contains the official course assignments, including theoretical problem sets and practical programming notebooks for the Machine Learning course.

---

## Repository Structure

```txt
.
├── HW1-Regression
│   ├── practical.ipynb              # Practical notebook for regression pipelines
│   └── theoretical.pdf              # Theoretical problem set for regression
├── HW2-MLP
│   ├── assets                       # Reference evaluation plots and diagrams
│   │   ├── decision_boundaries_ref.png
│   │   ├── regularization_comparison_ref.png
│   │   └── xor_convergence_ref.png
│   ├── practical
│   │   └── ML_HW2_MLP_1405_v3.ipynb # Multi-Layer Perceptrons assignment (Student Skeleton)
│   └── theoretical
│       └── ML_HW2_MLP_1405_v3.pdf   # Theoretical problem set for MLP
├── LICENSE
└── README.md

```

---

## Assignment Workflow & Setup

### Supported Environments

All practical assignments are designed and tested to execute across the following environments:

1. **Google Colab**
2. **Kaggle Notebooks** (Ensure GPU acceleration is selected if available)
3. **Local Environment** (Linux / macOS / Windows)

### Local Environment Setup

To configure a local Python environment, install the required dependencies:

```bash
conda create -n ml-course python=3.11 -y
conda activate ml-course
pip install numpy torch torchvision matplotlib scikit-learn tqdm jupyter

```

---

## Assignment Guidelines

1. **Submission Format:** Submit both your completed `.ipynb` file and the generated theoretical solution report in PDF format through the course LMS.
2. **Deterministic Verification:** Practical notebooks contain built-in test cells (`assert` statements and numerical checks). Ensure all verification cells execute without errors prior to submission.
3. **Integrity Policy:** All assignments must represent individual work. Collaboration on code implementation is strictly prohibited. Generative AI tools may only be consulted for conceptual clarification.