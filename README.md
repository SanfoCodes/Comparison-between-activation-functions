# 🔍 Comparing Activation Functions in Neural Networks

This repository contains the full codebase, experiments, visualizations, and theoretical analysis for the project:

**Mathematical Analysis and Theoretical Trade-offs of Activation Functions in Neural Networks:  
Convergence Behavior and Gradient Dynamics**

Developed as part of **DASC 5420 – Advanced Machine Learning**  
📍 Thompson Rivers University (TRU)

---

## 📌 Motivation

Activation functions play a critical role in neural network training by shaping gradient flow, convergence speed, and optimization stability.  
This project studies both **empirical performance** and **theoretical properties** of commonly used activation functions to understand their real-world trade-offs.

---

## 📚 Activation Functions Studied

The following five activation functions are analyzed:

- **ReLU**
- **Sigmoid**
- **Tanh**
- **Leaky ReLU**
- **Swish**

Each function is evaluated across identical architectures and training conditions.

---

## 🔬 Evaluation Criteria

We compare activation functions based on:

- Convergence speed  
- Training and test accuracy  
- Gradient flow behavior  
- Vanishing and exploding gradients  
- Smoothness and differentiability  
- Saturation effects  
- Stability during optimization  

---

## 📁 Repository Structure

```text
.
├── modelling/              # Model architecture, training loop, data loaders
│   ├── model_builder.py
│   ├── trainer.py
│   └── utils.py
│
├── visualization/          # Plotting tools
│   ├── loss_plots.py
│   ├── gradient_flow.py
│   ├── activation_derivatives.py
│   └── README.md
│
├── presentation/           # Theory, derivations, math notes
│   └── activation_analysis.md
│
├── main.ipynb              # Main Colab notebook (runs everything)
└── README.md               # You are here 🚀

```
---

## 🧪 How to Run (Google Colab)

1. Upload this repository or clone it into Google Colab.
2. Ensure CIFAR-10 can be downloaded via `torchvision.datasets`.
3. Open and run `main.ipynb` to:
   - Train neural network models using all five activation functions
   - Generate and save loss, accuracy, gradient flow, and derivative plots

---

## 🧠 Theory & Derivations

This project integrates theoretical and empirical analysis, including:
- Formal convergence conditions (e.g., Lipschitz continuity)
- Optimization landscape insights (plateaus, curvature, gradient norms)
- Activation derivative analysis and its impact on gradient flow
- Key results from the **TeLU paper** on smooth approximations of ReLU

All mathematical derivations and theoretical discussions are documented in:

`presentation/activation_analysis.md`

---

## 💾 Output Plots

All generated plots are automatically saved to:

`/MyDrive/tml_project/plots/`

This output path can be customized inside `main.ipynb`.

---

## 🔧 Requirements

- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- Google Colab (recommended)

---

## 📬 Contact

**Author:** Arpitha Thippeswamy  

**Team Members:**
- Sree Aryan SP  
- Zhang Jiayi  
- Shashank Manjunatha  

---

