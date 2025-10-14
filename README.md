# Superposition and Entanglement with Qiskit

This repository contains a Jupyter Notebook demonstrating **quantum superposition and entanglement** using **Qiskit**, a Python framework for quantum computing. The notebook provides hands-on examples to help students understand fundamental quantum computing concepts.

---

## 📁 Repository Contents

- `Qiskit_Superposition_Entanglement.ipynb` – Main notebook demonstrating:
  1. **Superposition** of a single qubit.
  2. **Entanglement** (Bell state) of two qubits.
  3. Optional experiments with quantum gates.

---

## 💻 About the Notebook

The notebook is divided into three main parts:

### **1. Installation**
Installs the required packages:
```python
!pip install qiskit
!pip install qiskit-aer
```

### **2. Imports**
Imports the necessary modules from Qiskit and visualization tools:
```python
from qiskit import QuantumCircuit, Aer, execute
from qiskit.visualization import plot_histogram, plot_bloch_multivector
from qiskit.quantum_info import Statevector
import matplotlib.pyplot as plt
```

### **3. Superposition Example**
- Creates a single qubit circuit.
- Applies a **Hadamard (H) gate** to place the qubit in superposition.
- Measures the qubit and plots the **histogram** of outcomes.
- Visualizes the **state on the Bloch sphere**.

### **4. Entanglement Example**
- Creates a 2-qubit circuit.
- Applies **H** to the first qubit, then **CNOT** to entangle both qubits.
- Measures both qubits and plots the **histogram**.
- Shows the **statevector** of the entangled qubits.

---

## 🎓 Student Tasks

After exploring the notebook, students can try these small tasks:

### **Task 1: Superposition**
- Create a single qubit circuit.
- Apply a Hadamard gate.
- Measure and plot the histogram.
- Observe equal probabilities for `0` and `1`.

### **Task 2: Entanglement**
- Create a 2-qubit circuit.
- Apply H to qubit 0, then CNOT (0→1).
- Measure and plot the histogram.
- Observe correlated outcomes (`00` or `11`).

### **Task 3: Experiment with Gates**
- Apply different gate combinations (e.g., H → X → H) on a single qubit.
- Measure and compare the results.
- Discuss how gate sequences affect measurement probabilities.

### **Bonus Task: GHZ State**
- Create a 3-qubit circuit.
- Apply H to qubit 0, then CNOT (0→1) and CNOT (1→2).
- Measure and plot the histogram.
- Observe outcomes `000` and `111` (3-qubit entanglement).

---

## 📊 Visualizations

The notebook includes visualizations for:
- **Bloch sphere** – Shows the qubit state for superposition.
- **Histogram** – Shows measurement probabilities for superposition and entangled states.

---

## 📝 How to Run

1. Clone the repository:
```bash
git clone <repository-url>
```
2. Open the notebook `Qiskit_Superposition_Entanglement.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
3. Run the cells step by step to explore **superposition**, **entanglement**, and perform **student tasks**.

---

## 🔗 References

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [Quantum Computing Basics](https://qiskit.org/learn/intro-qc-qh/)
