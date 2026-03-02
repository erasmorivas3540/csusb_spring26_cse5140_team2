
# Environment Summary – CSE 5140 Team 2

This document describes the computational environment used to execute all final experiments
for the CSE 5140 Computational Intelligence Project.

All reported results were generated on the instructor-managed NRP JupyterHub environment
to ensure reproducibility and fairness across teams.

---

## 1. Platform

- Platform: National Research Platform (NRP) – JupyterHub
- Execution Mode: Instructor-managed shared environment
- Hardware: Instructor-specified configuration (CPU/GPU/RAM fixed across teams)

---

## 2. NRP Jupyter Image

- Image Name: NRP Stack PyTorch2

---

## 3. Python Version

```bash
python --version
```

Output: `Python 3.10.10`

## 4. Key Libraries and Versions

The following command was used to capture installed packages:
```Bash
pip list --format=freeze > requirements_freeze.txt
```
Below are the primary libraries used in this project:

| Library        | Version |
|----------------|---------|
| numpy          | 1.23.5  |
| pandas         | 2.0.0   |
| scikit-learn   | 1.2.2   |
| torch          | 2.0.0   |


Full dependency list is available in `./requirements_freeze.txt`
