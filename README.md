# CSE 5140 – Computational Intelligence

🧠  ## Team 2 –  Computational Intelligence Project

---

🚀 Introduction

---

This repository contains the full implementation for the **CSE 5140 Semester Project** for Computational Intelligence.

The will design, implement, and rigorously compare the three core paradigms of Computational Intelligence:

- **Neural Networks (NN)**
- **Evolutionary Algorithms (EA)**
- **Fuzzy Systems (FS)**

Neural Networks are computational models inspired by the human brain that learn patterns from data, Evolutionary Networks use principles of natural selection 
and genetic adaptation to optimize solutions over time, and Fuzzy Systems apply approximate reasoning with degrees of truth rather than binary logic to 
handle uncertainty and imprecision in complex problems.

--

# 🧠 Phase Overview

## Phase 1 – Neural Networks

- Baseline model (Linear Regression)
- PyTorch Neural Network model
- Feature importance (SHAP / permutation / weight analysis)
- Metrics: RMSE, MAE, R²

## Phase 2 – Evolutionary Algorithms

- Genetic Algorithm for:
  - Hyperparameter tuning and/or
  - Feature subset optimization
- Fitness convergence visualization
- Quantified performance improvement over Phase 1

## Phase 3 – Fuzzy Systems

- Fuzzy Inference System (scikit-fuzzy)
- Rule base documentation
- Interpretability analysis
- Performance comparison vs NN/EA

## Final Phase – Integrated Comparison

- Normalized metric comparison (R², MAPE)
- Runtime comparison
- Statistical validation (paired t-test / bootstrap)
- Trade-off analysis (accuracy vs cost vs interpretability)

---

- 🧠 Learning these methods enables you to solve complex real-world problems by modeling patterns, uncertainty, and optimization challenges effectively.

- 📋  Understanding Neural Networks, Evolutionary Networks, and Fuzzy Systems strengthens your ability to design intelligent, adaptive, and data-driven systems.

- 🤖 Mastering these approaches provides a strong foundation for advanced research in artificial intelligence.

# 🚀 How to Run the Project (NRP Required)

All final results must be executed on **NRP.ai using the NRP Stack PyTorch2 environment**.

---

## Step 1 – Log into NRP

1. Go to: https://nrp.ai  
2. Log into your CSUSB NRP account.  
3. Launch **Jupyter Notebook** using the NRP Stack PyTorch2 environment. 

---

## Step 2 – Clone or Pull Repository

Inside the NRP Jupyter terminal:

```bash
git clone https://github.com/DrAlzahraniProjects/csusb_spring26_cse5140_team2.git
```

If already cloned:
```bash
cd csusb_spring26_cse5140_team2
git pull
```

## Step 2 – Clone or Pull Repository
```bash
cd csusb_spring26_cse5140_team2
```

## Step 4 – Open and Run Notebooks
```code
NN_Analysis.ipynb
```
Run all cells top-to-bottom
(Kernel → Restart & Run All)
