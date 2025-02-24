# Active Learning for MNIST Classification Using CNN

## Overview
This project implements an **active learning framework** for image classification using a **Convolutional Neural Network (CNN)** on the **MNIST** dataset. The goal is to optimize the model's performance by selecting the most informative samples for labeling, rather than training on the entire dataset.

## Features
- **CNN Implementation**: A deep learning model for digit classification.
- **Active Learning Strategies**:
  - **Uniform Sampling** (Random selection)
  - **Max Entropy** (Selects samples with the highest uncertainty)
  - **BALD (Bayesian Active Learning by Disagreement)** (Selects samples with the highest information gain)
- **Performance Evaluation**: Compares accuracy across different active learning strategies.

## Technologies Used
- Python
- PyTorch
- NumPy
- torchvision (for MNIST dataset)
- scikit-learn
- skorch
- modAL (for active learning)
- Matplotlib & Seaborn (for visualization)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install required dependencies:
   ```bash
   pip install torch torchvision numpy scikit-learn skorch modAL matplotlib seaborn
   ```

## Usage
Run the script using:
```bash
python main.py
```

## Output
- The script will display model accuracy at each active learning step.
- A plot comparing the accuracy of different active learning strategies.

## Contact
For any inquiries or suggestions, feel free to reach out!

---

This README provides a comprehensive guide to your project. Let me know if you’d like any modifications!

