# Quantum Computing Fundamentals

A collection of hands-on quantum computing notebooks implemented using Qiskit.

This repository documents my progression through the foundations of quantum computing and quantum information science, focusing on practical experimentation, simulation, and reproducible computational workflows.

The goal of this repository is to build a strong foundation in quantum computing before progressing to more advanced topics such as quantum noise analysis, error mitigation, quantum error correction, and topological quantum computation.

---

## Repository Structure

```text
quantum-computing-fundamentals/

├── Basics/
│   ├── hadamard.ipynb
│   ├── pauli_x_gate.ipynb
│   ├── pauli_z_gate.ipynb
│   ├── two_qubit_basics.ipynb
│   └── bell_state.ipynb
│
├── Simulators/
│   ├── statevector_simulator.ipynb
│   └── qasm_simulator.ipynb
│
├── Algorithms/
│   └── grovers_algorithm.ipynb
│
├── README.md
└── .gitignore
```

---

## Current Contents

### Basics

#### Hadamard Gate and Quantum Superposition

Demonstrates how a Hadamard gate creates an equal superposition of quantum states and introduces the probabilistic nature of quantum measurement.

#### Pauli-X Gate (Quantum NOT)

Explores deterministic state transitions and the quantum analogue of the classical NOT operation.

#### Pauli-Z Gate (Phase Flip)

Introduces phase transformations and highlights the importance of phase information in quantum systems.

#### Two-Qubit Quantum Systems

Examines multi-qubit state representations and measurement outcomes in composite quantum systems.

#### Bell State and Quantum Entanglement

Demonstrates quantum entanglement through Bell states and explores non-classical correlations between qubits.

---

### Simulators

#### Statevector Simulator

Investigates the mathematical representation of quantum states through state vectors, amplitudes, probabilities, and phase information.

Topics include:

* Quantum amplitudes
* Probability calculations
* Statevector visualization
* Bloch sphere representations
* Measurement probability analysis

#### QASM Simulator

Introduces measurement-based quantum simulation and statistical analysis of repeated circuit executions.

Topics include:

* Quantum measurements
* Shot-based simulations
* Probability distributions
* Statistical convergence
* Experimental validation of theoretical predictions

---

### Quantum Algorithms

#### Grover's Search Algorithm

Implements Grover's quantum search algorithm using Qiskit and demonstrates quantum amplitude amplification.

Topics include:

* Oracle construction
* Diffusion operators
* Amplitude amplification
* Search-space reduction
* Measurement analysis

---

## Planned Additions

### Quantum Information Foundations

* Quantum Measurement
* Density Matrices
* Mixed States
* Fidelity
* Quantum Channels
* Decoherence

### Quantum Computing

* Deutsch–Jozsa Algorithm
* Bernstein–Vazirani Algorithm
* Quantum Fourier Transform

### Noise and Error Analysis

* Bit-Flip Noise
* Phase-Flip Noise
* Depolarizing Noise
* Amplitude Damping
* Noise Characterization

---

## Related Research Projects

### Quantum Noise Analysis and Error Mitigation

A dedicated research-oriented project investigating:

* Quantum noise models
* Fidelity degradation
* Error mitigation techniques
* Noise-aware simulation
* Performance benchmarking

### Kitaev Chain and Majorana Zero Modes

A computational condensed matter physics project exploring:

* Kitaev chain models
* Topological phase transitions
* Majorana edge modes
* Topological quantum computation

---

## Tools and Technologies

* Python
* Qiskit
* Qiskit Aer
* NumPy
* Matplotlib
* Jupyter Notebook
* Git
* GitHub
* VS Code

---

## Purpose of This Repository

* Develop a strong foundation in quantum computing
* Build practical intuition through simulation and experimentation
* Establish core knowledge in quantum information science
* Prepare for advanced research projects in quantum technologies
* Maintain a well-documented and reproducible learning portfolio

---

## Notes

* Virtual environments are intentionally excluded from version control.
* All notebooks are designed to be reproducible and self-contained.
* This repository serves as the foundational component of a broader quantum computing research portfolio.

---

## Long-Term Direction

This repository represents the first stage of a broader research pathway:

Quantum Computing Fundamentals

→ Quantum Information Science

→ Quantum Noise Analysis and Error Mitigation

→ Quantum Error Correction

→ Topological Phases of Matter

→ Majorana Zero Modes

→ Topological Quantum Computation

The long-term objective is to contribute to the development of fault-tolerant quantum technologies through the intersection of quantum information science and condensed matter physics.
