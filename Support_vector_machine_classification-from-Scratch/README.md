# 📈 Support Vector Machine (SVM) From Scratch

This project implements a **Support Vector Machine (SVM) Classifier from scratch** using Python and NumPy without relying on Scikit-learn's built-in `SVC` implementation.

The goal of this project is to understand how SVM works internally by implementing the algorithm step by step, including the maximum-margin optimization process.

---

# 📌 Project Overview

This implementation includes:

- Support Vector Machine (SVM) Classifier
- Maximum Margin Classification
- Gradient Descent Optimization
- L2 Regularization
- Binary Classification
- Model Prediction
- Model Evaluation

---

# 🚀 Features

- ✅ Support Vector Machine implemented from scratch
- ✅ Binary Classification
- ✅ Maximum Margin Hyperplane
- ✅ Hinge Loss Optimization
- ✅ Gradient Descent
- ✅ L2 Regularization
- ✅ Vectorized NumPy Operations
- ✅ Supports multiple input features

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn (only for dataset loading, train-test split and evaluation)
- Jupyter Notebook

---

# 🧠 How It Works

The model follows these steps:

1. Initialize weights and bias.
2. Convert class labels to **-1** and **1**.
3. Compute the decision function:

```text
f(x) = w · x - b
```

4. Check whether each sample satisfies the margin condition:

```text
y(w · x - b) ≥ 1
```

5. Update the weights and bias using Gradient Descent and Hinge Loss.
6. Repeat for the specified number of iterations.
7. Predict the class using:

```text
sign(w · x - b)
```

---

# 📁 Project Structure

```text
Support Vector Machine/
│
├── svm.ipynb
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/mohammadfawazgoat/Machine-Learning-Models-From-Scratch
```

Navigate to the project:

```bash
cd Machine-Learning-Models-From-Scratch
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📚 What I Learned

- Support Vector Machines (SVM)
- Maximum Margin Classification
- Hinge Loss
- L2 Regularization
- Gradient Descent
- Binary Classification
- Decision Boundary
- Vectorized NumPy Implementation

---

# 🚀 Future Improvements

- Soft Margin SVM
- Kernel SVM (Linear, Polynomial, RBF)
- Multi-class Classification
- Hyperparameter Tuning
- Visualization of Decision Boundaries

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome!

---

# 📜 License

This project is licensed under the MIT License.
