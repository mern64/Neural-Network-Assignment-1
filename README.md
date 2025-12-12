# STINK 3014 Neural Networks - Assignment #1

## 📄 Overview
This repository contains the practical implementation for **Assignment #1** of the **STINK 3014 (Neural Networks)** course. The project involves building a **Perceptron Model** to predict whether a small animal will approach an object based on specific visual cues.

## 🤖 Model Description
The model is a single-layer Perceptron trained to classify inputs into two categories:
* **Approach**
* **Not Approach**

### Input Features
The model analyzes three binary inputs:
1.  **Size (x1)**: Is the object small? (1 = Small, 0 = Not Small)
2.  **Color (x2)**: Is the object red? (1 = Red, 0 = Not Red)
3.  **Movement (x3)**: Is it moving? (1 = Move, 0 = Stationary)

## ⚙️ Hyperparameters
* **Learning Rate ($\eta$)**: 0.06 (Selected for balance between speed and stability).
* **Epochs**: 10 (Sufficient for convergence based on trials).
* **Initial Weights**: `[0.1, -0.2, 0.5]` representing the initial importance of Size, Color, and Movement respectively.

## 📂 Files Included
* **`Assignment 1.py`**: The main Python script. It includes:
    * The Perceptron training loop.
    * Matplotlib code to visualize weight updates and error reduction.
    * An interactive prediction tool to test new inputs.

## 🚀 How to Run
Prerequisites: Python 3.x and Matplotlib.

```bash
# Run the script
python "Assignment 1.py"