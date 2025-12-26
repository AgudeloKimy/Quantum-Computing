# Quantum Computing Course Notes and Code

Repository for the course **Fundamentals of Quantum Computing** (Prof. Aldo Quelopana, October 2025).

Prepared by: **Kimy Agudelo Jaramillo**

## Description

This repository contains:
- The complete course notes in PDF format: theoretical foundations of quantum computing with a focus on the **gate-based (circuit) model**.
- Jupyter notebooks (`.ipynb`) with practical implementations of the key concepts and algorithms discussed in the notes, using **Qiskit** (IBM's open-source quantum computing framework).

The notes cover topics from basic quantum mechanics postulates to advanced algorithms such as Deutsch-Jozsa, Grover's search, and the Quantum Fourier Transform. 

## How to Run the Notebooks

You have several options (no local installation required):

1. **Recommended: Google Colab** (easiest)
   - Open any `.ipynb` file directly on GitHub.
   - Click "Open in Colab" (GitHub usually shows this button).
   - Run all cells – everything works out of the box (Qiskit is pre-installed on Colab).

2. **Locally with Jupyter**
   ```bash
   git clone https://github.com/AgudeloKimy/Quantum-Computing.git
   cd Quantum-Computing
   pip install -r requirements.txt
   jupyter notebook
   
