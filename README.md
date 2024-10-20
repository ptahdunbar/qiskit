# **IBM Qiskit Quantum Computing Notebooks**

This repository contains a set of **Jupyter Notebooks** designed to introduce and explore **quantum computing** concepts using **Qiskit**, IBM’s open-source quantum computing framework. Each notebook covers a unique aspect of quantum computation, from basic "Hello World" circuits to more advanced experiments such as the **CHSH Inequality** and **Qiskit Runtime Lab**.

---

## **Table of Contents**
1. [Introduction and Setup](#introduction-and-setup)
2. [Notebooks Overview](#notebooks-overview)
3. [Quantum Concepts in the Notebooks](#quantum-concepts-in-the-notebooks)
4. [How to Run the Notebooks](#how-to-run-the-notebooks)
5. [Additional Resources](#additional-resources)

---

## **Introduction and Setup**

This repository provides a hands-on approach to learning quantum computing. To run the notebooks, ensure you have the following prerequisites:

- **Qiskit**: Install it using:
  ```bash
  pip install qiskit[visualization] qiskit-aer qiskit-ibm-runtime

## **Notebooks Overview**

### 1. **firstStepsIntoQuantumComputing.ipynb**

This notebook introduces the **foundations of quantum circuits**, focusing on key concepts such as **superposition**, **entanglement**, and **measurement**.

#### **Summary:**
- **Qubits**: Create quantum circuits with single and multiple qubits.
- **Superposition**: Use the **Hadamard gate (H)** to create superposition states.
- **Entanglement**: Use **CNOT gates** to entangle two qubits.
- **Measurement**: Measure quantum states and store the results in classical bits.
- **Simulation**: Execute the circuits on a **local Aer simulator**.
- **Visualization**: Use **matplotlib** to visualize circuit diagrams and results.

---

### 2. **welcomeAndHelloWorld.ipynb**

This notebook provides a simple "Hello World" program in the context of quantum computing and demonstrates basic quantum operations.

#### **Summary:**
- **Single-Qubit Gates**: Apply **Pauli-X (NOT)** and **Hadamard gates**.
- **Two-Qubit Circuits**: Use **CNOT gates** for controlled operations.
- **Visualization**: Display circuits and results with **matplotlib**.
- **Grader Exercises**: Submit answers using the **Qiskit Grader**.

---

### 3. **Qiskit Runtime Lab (I2).ipynb**

This notebook focuses on **Qiskit Runtime**, a cloud-based service for efficient quantum circuit execution on IBM hardware.

#### **Summary:**
- **Setup**: Configure and connect to **Qiskit Runtime** services.
- **Backend Management**: Use the **least busy backend** for faster execution.
- **Execution**: Run circuits on real quantum hardware using Qiskit Runtime.

---

### 4. **The Transpiler (I3).ipynb**

This notebook explores **circuit optimization** through Qiskit’s transpiler, preparing circuits for hardware execution.

#### **Summary:**
- **Optimization**: Use the transpiler to reduce gate depth and circuit size.
- **Comparison**: Test the impact of different **transpiler settings**.
- **Deployment**: Prepare circuits for noisy quantum hardware.

---

### 5. **CHSH_Inequality_(B2).ipynb**

This notebook examines the **CHSH Inequality**, demonstrating quantum entanglement and the concept of **non-locality**.

#### **Summary:**
- **Entanglement**: Build circuits that create entangled qubit pairs.
- **CHSH Inequality**: Verify the quantum violation of the classical CHSH inequality.
- **Observables**: Measure and compare quantum vs. classical results.
- **Execution**: Run the experiment on real quantum hardware using **Estimator Primitives**.

