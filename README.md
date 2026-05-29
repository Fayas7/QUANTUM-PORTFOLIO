# Quantum Computing Portfolio

This repository contains hands-on quantum computing experiments and projects
implemented using **Qiskit**.  
It documents my step-by-step journey from quantum fundamentals to
quantum algorithms and quantum machine learning.

The focus of this portfolio is on **clear understanding, clean implementation,
and reproducible experiments** rather than theory-heavy exposition.

-------------------------------------

## 📂 Repository Structure

```text
quantum-portfolio/
├── Basics/
│   ├── hadamard.ipynb
│   ├── pauli_x_gate.ipynb
│   ├── pauli_z_gate.ipynb
│   ├── two_qubit_basics.ipynb
│   └── bell_state.ipynb
│
├── Simulators/
│   └── statevector_simulator.ipynb
    ├── qasm_simulator.ipynb
│
├── Algorithms/
│   └── Grover's Algorithm
│
├── README.md
└── .gitignore

```



--------------------------------------

## 🧪 Current Contents

### 📚 Basics

#### Hadamard Gate and Quantum Superposition

Demonstrates how a Hadamard gate creates an equal superposition of |0⟩ and |1⟩. Measurement statistics are visualized using histograms, illustrating the probabilistic nature of quantum mechanics.

#### Pauli-X Gate (Quantum NOT)

Shows how the Pauli-X gate deterministically flips a qubit from |0⟩ → |1⟩, acting as the quantum equivalent of a classical NOT gate.

#### Pauli-Z Gate (Phase Flip)

Demonstrates how the Pauli-Z gate changes the phase of a qubit without altering measurement probabilities, highlighting the importance of phase information in quantum systems.

#### Two-Qubit Quantum System

Introduces multi-qubit states and demonstrates how measurements represent the combined quantum state of multiple qubits.

#### Bell State and Quantum Entanglement

Explores quantum entanglement through the Bell state, showing how two qubits can exhibit perfect correlations despite individually random measurement outcomes.

---

### ⚙️ Simulators

#### Statevector Simulator

Explores the mathematical representation of quantum states using Qiskit's Statevector simulator. Demonstrates quantum amplitudes, probability calculations, superposition, phase information, Bloch sphere visualization, and the relationship between amplitudes and measurement probabilities.

#### QASM Simulator

Introduces measurement-based quantum simulation using Qiskit Aer. Demonstrates quantum measurements, shots, probability distributions, and how repeated circuit executions reveal statistical patterns that converge toward theoretical predictions.

---

### 🧠 Quantum Algorithms

#### Grover's Search Algorithm

Implements Grover's quantum search algorithm using Qiskit. Demonstrates amplitude amplification and quantum search techniques, showing how a marked state can be found with significantly fewer operations than a classical brute-force search. The notebook explores oracle construction, diffusion operators, and measurement analysis of the final quantum state.

---

### 🚀 Upcoming Topics

* Measurement Statistics and Convergence Analysis
* Bell State Simulation
* Noisy Quantum Simulations
* Simulator Comparisons
* Quantum Noise Analysis
* Quantum Error Mitigation
* Additional Quantum Algorithms

--------------------------------------
## 🛠 Tools & Technologies

- **Python**
- **Qiskit**
- **Qiskit Aer**
- **Jupyter Notebook**
- **VS Code**
- **Git & GitHub**


---------------------------------------

## 🎯 Purpose of This Portfolio

- Build strong fundamentals in quantum computing
- Develop practical intuition through experiments
- Progress toward quantum algorithms and quantum machine learning
- Create a job-ready, well-documented GitHub portfolio

---

## 📌 Notes

- Virtual environments (`.venv`) are intentionally excluded from the repository
- All notebooks are designed to be readable and self-explanatory

---

📈 *This repository will be continuously updated as part of a structured
quantum computing learning roadmap.*
