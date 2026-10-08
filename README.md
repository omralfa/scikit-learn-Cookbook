# scikit-learn Cookbook — Code Reproduction & Theoretical Deep-Dive

**Nama:** Omar Al Farizy Hutagalung
**NIM:** 101032300034
**Mata Kuliah:** Machine Learning

---

## About This Repository

Repository ini dibuat untuk memenuhi Tugas 2 Machine Learning berupa
code reproduction dan theoretical deep-dive berdasarkan buku:

**scikit-learn Cookbook, Third Edition**  
**Author:** John Sukup

Repository ini berisi implementasi kode, penjelasan konsep, analisis hasil,
dan kesimpulan dari setiap chapter yang dipelajari.

---

## Environment

- Python 3.12.10
- scikit-learn 1.9.1
- NumPy
- Pandas
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Chapter Overview

### Chapter 1 — Common Conventions and API Elements of scikit-learn

Membahas dasar API scikit-learn, termasuk estimator, transformer, custom
components, pipeline, common API methods, hyperparameter tuning, metadata,
dan best practices.

Notebook:
`Chapter_1/Chapter_1_Common_Conventions.ipynb`

---

### Chapter 2 — Pre-Model Workflow and Data Preprocessing

Membahas proses persiapan data sebelum modeling, meliputi data cleaning,
missing data, scaling, categorical encoding, pipeline, dan feature
engineering.

Notebook:
`Chapter_2/Chapter_2_Pre_Model_Workflow.ipynb`

---

### Chapter 3 — Dimensionality Reduction Techniques

Membahas dimensionality reduction menggunakan feature selection,
feature extraction, PCA, LDA, dan t-SNE.

Notebook:
`Chapter_3/Chapter_3_Dimensionality_Reduction.ipynb`

---

### Chapter 4 — Building Models with Distance Metrics and Nearest Neighbors

Membahas distance metrics dan algoritma K-Nearest Neighbors (KNN),
termasuk Euclidean, Manhattan, Minkowski, Cosine, evaluasi model,
dan hyperparameter tuning.

Notebook:
`Chapter_4/Chapter_4_Nearest_Neighbors.ipynb`

---

### Chapter 5 — Linear Models and Regularization

Membahas Linear Regression, Ridge, Lasso, ElasticNet, regularization,
bias-variance trade-off, dan polynomial regression.

Notebook:
`Chapter_5/Chapter_5_Linear_Models.ipynb`

---

## Repository Structure

```text
scikit-learn-Cookbook/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── Chapter_1/
│   └── Chapter_1_Common_Conventions.ipynb
│
├── Chapter_2/
│   └── Chapter_2_Pre_Model_Workflow.ipynb
│
├── Chapter_3/
│   └── Chapter_3_Dimensionality_Reduction.ipynb
│
├── Chapter_4/
│   └── Chapter_4_Nearest_Neighbors.ipynb
│
└── Chapter_5/
    └── Chapter_5_Linear_Models.ipynb