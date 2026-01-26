# 🔍 Kernel Method Comparisons with SVM

This project compares the performance of **Support Vector Machine (SVM)** models using different kernels:
- **Linear Kernel**
- **Polynomial Kernel**
- **Radial Basis Function (RBF) Kernel**
- **Sigmoid Kernel**

We apply these kernels to two datasets from the UCI repository:
1. **Semeion Handwritten Digit Dataset** (`/content/semeion.data`)  
2. **Spambase Dataset** (`/content/spambase.data`)  

---

## 🚀 Project Overview

SVM is a powerful supervised machine learning algorithm, and the choice of **kernel function** strongly affects its performance.  
- The **linear kernel** works well when data is linearly separable.  
- The **polynomial kernel** introduces non-linear decision boundaries.  
- The **RBF kernel** maps data into an infinite-dimensional space for highly flexible separation.  
- The **sigmoid kernel** mimics neural network activation functions.  

In this project, we:
- Preprocess both datasets  
- Train SVM models with **Linear, Polynomial, RBF, and Sigmoid kernels**  
- Evaluate using **accuracy, confusion matrix, and classification report**  
- Compare results across kernels and datasets  

---

## ⚙️ Setup

### 1. Clone the Repository
```bash
git clone https://github.com/sidharthh-a/svm-kernel-comparison.git
cd svm-kernel-comparison
