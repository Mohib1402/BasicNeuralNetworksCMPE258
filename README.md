# BasicNeuralNetworksCMPE258

---

```markdown
# 🧠 Deep Learning From Scratch – Multi-Framework Nonlinear Regression

## 🎯 Assignment Overview

This project implements a **3-layer deep neural network for nonlinear regression** using multiple frameworks:  
**NumPy, PyTorch (manual, class-based, Lightning), and TensorFlow (low-level, Sequential, Functional)**.

We use a custom 3-variable nonlinear function and train all networks to approximate it using synthetic data.

📅 **Due Date:** March 6  
📌 **Points:** 100  
🎥 **Video:** Full walkthrough of all Colabs [📺 Watch here](https://youtube.com/your-final-video-link)

---

## 🧪 Problem Statement

Train a deep neural network to approximate this nonlinear function:

\[
\text{target} = \sin(x) \cdot \log(y + 1) + x^2 - y \cdot z
\]

- **Input Variables:** \(x, y, z\)  
- **Target:** Nonlinear continuous value  
- **Goal:** Approximate target using a 3-layer neural network  
- **Bonus:** 4D plot showing how inputs relate to output

---

## 📁 Colab Notebooks

| Colab ID | Title | Framework | Description |
|----------|-------|-----------|-------------|
| [C1](https://colab.research.google.com/drive/1Iz6xwR_9XuEcQg80Lg0wHH_6fBAYmm7D?usp=sharing) | NumPy From Scratch | NumPy | Manual 3-layer NN using custom backpropagation and chain rule |
| [C2](https://colab.research.google.com/drive/1yMGM6MnpSieRpVXwiUY1zpGJ9j6ZA9mP?usp=sharing) | PyTorch Manual | PyTorch | Uses autograd, manual weight updates, no built-in layers |
| [C3](https://colab.research.google.com/drive/1GAKD7rg7lPmfudKluOai6JH-QMEVGinh?usp=sharing) | PyTorch Class-Based | PyTorch | Clean class-based `nn.Module` implementation |
| [C4](https://colab.research.google.com/drive/1kkZO7kkpjV7LBfEdEz_4x_6YtYzmFr-P?usp=sharing) | PyTorch Lightning | Lightning | Structured training using `LightningModule` and `Trainer` |
| [C5](https://colab.research.google.com/drive/1rB-ULg-UTUw30LMxtJiQ5v_vEEpN9XwF?usp=sharing) | TensorFlow Low-Level | TensorFlow | Uses `tf.einsum`, manual training with `GradientTape` |
| [C6](https://colab.research.google.com/drive/1FRQJDcoSPVg_yLxC4TGhrxfR_7kom_WD?usp=sharing) | TensorFlow Sequential API | TensorFlow | High-level `Sequential` model using `Dense` and `fit()` |
| [C7](https://colab.research.google.com/drive/1EBNzu-BpMERwUZRbep0MII2yB6G_42UL?usp=sharing) | TensorFlow Functional API | TensorFlow | Flexible Functional API with explicit input/output layers |

---

## 🧠 Model Architecture

```
Input (3D) → Dense(64) → ReLU → Dense(32) → ReLU → Dense(1)
```

- Used across all frameworks for consistency  
- Ensures apples-to-apples comparison of different APIs

---

## 📊 Dataset & Visualization

- 1,000 synthetic samples of \(x, y, z\)
- Output is calculated using the custom nonlinear equation
- Colabs include 4D plots using `matplotlib` with color-coded target

---

## ✅ Requirements Covered

- ✅ Used **3-layer network** in all implementations
- ✅ Used **TensorFlow `einsum`** in `C5`
- ✅ Used a **3-variable nonlinear function**
- ✅ Included **4D visualization**
- ✅ Each notebook demonstrates training loss + output
- ✅ All Colabs and explanation video are public

---

## 🎥 Video Walkthrough

🔗 [**Watch the full video walkthrough here**](https://youtube.com/your-final-video-link)

Covers:
- Problem explanation
- Colab-by-Colab walkthrough
- Key highlights in each implementation
- Final results and GitHub check-in proof

---

## 🚀 How to Run

Each notebook is self-contained:
- Open in Google Colab
- Run all cells sequentially
- Observe 4D plot and final loss curve

---

## 🙌 Author

Submitted by [Your Name]  
MS Software Engineering, San José State University  
Spring 2025

---

```

