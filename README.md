# A Deep Learning Approach to Solve Cubic Equations using PyTorch

This project demonstrates a beginner-friendly deep learning approach to solving cubic equations of the form:

ax³ + bx² + cx + d = 0

Instead of using traditional mathematical formulas, a neural network is trained using PyTorch to *learn* the value of `x` that makes the equation output close to zero. The solution is obtained through optimization using gradient descent.

---

## Objective

The objective of this project is to show how deep learning concepts such as trainable parameters, loss functions, activation functions, and optimizers can be applied to a mathematical problem.

This work was completed as part of a learning task after completing a course on CognitiveClass.ai.

---

## Approach Used

- The unknown variable `x` is treated as a **learnable parameter**
- A neural network is defined with:
  - One trainable parameter (`x`)
  - ReLU activation function
- The cubic equation output is used to compute loss
- **Stochastic Gradient Descent (SGD)** is used to minimize the loss
- Training continues until the equation output approaches zero

This demonstrates optimization-based learning using deep learning tools.

---

## Technologies and Tools

- Python
- PyTorch
- Google Colab
- Matplotlib (for loss visualization)

---

## Model Details

- **Framework:** PyTorch
- **Optimizer:** Stochastic Gradient Descent (SGD)
- **Activation Function:** ReLU
- **Loss Function:** Mean Squared Error (MSE)
- **Training Output:** Loss curve showing convergence

---

## Learning Verification

Learning is verified using a **loss vs epochs curve**:
- The loss decreases steadily during training
- This confirms that SGD is successfully optimizing the value of `x`
- The final learned value of `x` approximately satisfies the cubic equation

---

## Files in This Repository

- `cubic_equation_solver_pytorch.ipynb`  
  Google Colab notebook containing the complete PyTorch implementation

- `cognitiveclass_100_percent.png`  
  Screenshot showing 100% completion of the CognitiveClass.ai course

- `README.md`  
  Project documentation

---

## How to Run the Project

1. Open the notebook using Google Colab or Jupyter Notebook
2. Run all cells sequentially from top to bottom
3. Observe:
   - Training loss decreasing over epochs
   - Final learned value of `x` printed at the end

No additional setup is required if running on Google Colab.

---

## Notes

- This project focuses on demonstrating **deep learning concepts**, not analytical equation solving
- The solution obtained is an **approximate numerical root**
- Due to floating-point precision and optimization methods, results may slightly vary

---

## Educational Purpose

This project is created purely for **educational and learning purposes** to understand how neural networks and gradient descent can be applied beyond traditional prediction tasks.

---

## Author

Name : Jairaj R  
Email : jairajrenjith@gmail.com
