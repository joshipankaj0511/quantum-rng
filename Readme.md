# Quantum Random Number Generator (QRNG)

This project demonstrates how to generate **true random numbers** using **quantum superposition** with Qiskit.

## 🔹 How It Works
- A single qubit is initialized in state |0⟩.
- A Hadamard gate (H) puts it into superposition (50% |0⟩ and 50% |1⟩).
- Measurement collapses the qubit randomly to |0⟩ or |1⟩.
- Repeating this experiment yields random bits.

## 🔹 Features
- Generate random bits using Qiskit’s quantum simulator.
- Convert bit strings into random integers.
- Visualize randomness distribution with histogram.

## 🔹 Run the Notebook
Install dependencies:
```bash
pip install -r requirements.txt
