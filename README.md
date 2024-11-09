# **IBM Qiskit Quantum Computing Notebooks**

This repository contains a set of **Jupyter Notebooks** designed to introduce and explore **quantum computing** concepts using **Qiskit**, IBM's open-source quantum computing framework. Each notebook covers a unique aspect of quantum computation, from basic "Hello World" circuits to more advanced experiments such as the **CHSH Inequality** and **Qiskit Runtime Lab**.

## **Table of Contents**
1. [Introduction and Setup](#introduction-and-setup)
2. [Notebooks Overview](#notebooks-overview)
3. [Additional Resources](#additional-resources)

## **Introduction and Setup**

This repository provides a hands-on approach to learning quantum computing. To run the notebooks, ensure you have the following prerequisites:

### **Google Colab for a Seamless Experience!**

To make your workshop experience as smooth as possible, we'll be using Google Colab—a powerful, browser-based platform. No installations are needed, so whether you're a beginner or experienced, you can feel confident about joining. All you need is access to Google Colab and an IBMid, which will allow you to run quantum programs directly on IBM's actual quantum computers!

### **Here's what to do:**
- Access Google Colab: https://colab.google/ and you'll be all set to run code from your browser.
- Create Your Free IBMid: https://www.ibm.com/mysupport/s/my-cases will be your gateway to hands-on quantum programming, and the best part? It's free!

### **No Quantum Experience? No Problem!**

If quantum computing is completely new to you, that's exactly why we're here. These workshops are designed to introduce and explain this emerging technology, with IBM and computing experts on hand to guide you through each step. You'll be in good company, and we'll ensure that you gain a foundational understanding.

With these tools in place, you'll be set up for a truly interactive experience. Whether this is your first step into quantum or you're looking to expand your skills, this approach is designed to support every level.

## **Notebooks Overview**

## Beginner

### 1. **firstStepsIntoQuantumComputing(B1).ipynb** 
https://colab.research.google.com/drive/1TVjaxLuiJJKGIQmiwYZZUj59rrlDrHVV?usp=drive_link

Note: Make sure to click 'Copy to Drive' to work out of your own Colab notebook.

This notebook introduces the **foundations of quantum circuits**, focusing on key concepts such as **superposition**, **entanglement**, and **measurement**.

##### **Summary:**
- **Qubits**: Create quantum circuits with single and multiple qubits.
- **Superposition**: Use the **Hadamard gate (H)** to create superposition states.
- **Entanglement**: Use **CNOT gates** to entangle two qubits.
- **Measurement**: Measure quantum states and store the results in classical bits.
- **Simulation**: Execute the circuits on a **local Aer simulator**.
- **Visualization**: Use **matplotlib** to visualize circuit diagrams and results.

---

### 2. **cHSHInequality(B2).ipynb**
https://colab.research.google.com/drive/1ogAAOY4seJU-UuSpcGKNyMCar9fPUJeP#scrollTo=NljfYt205xz3

Note: Make sure to click 'Copy to Drive' to work out of your own Colab notebook.

This notebook examines the **CHSH Inequality**, demonstrating quantum entanglement and the concept of **non-locality**.

#### **Summary:**
- **Entanglement**: Build circuits that create entangled qubit pairs.
- **CHSH Inequality**: Verify the quantum violation of the classical CHSH inequality.
- **Observables**: Measure and compare quantum vs. classical results.
- **Execution**: Run the experiment on real quantum hardware using **Estimator Primitives**.

---

## Intermediate

### 3. **welcomeAndHelloWorld(I1).ipynb**
https://colab.research.google.com/drive/1SsY_rfQMNL4pa5RxArTjuDhJcSbOzIAu#scrollTo=UTs9--QJd1Y4

Note: Make sure to click 'Copy to Drive' to work out of your own Colab notebook.

This notebook provides a simple "Hello World" program in the context of quantum computing and demonstrates basic quantum operations.

##### **Summary:**
- **Single-Qubit Gates**: Apply Pauli-X (NOT) and Hadamard gates.
- **Two-Qubit Circuits**: Use CNOT gates for controlled operations.
- **Visualization**: Display circuits and results with matplotlib.
- **Grader Exercises**: Submit answers using the Qiskit Grader.

---

### 4. **qiskitRuntimeLab(I2).ipynb**
https://colab.research.google.com/drive/1z4x5_F_uRyPwYdbWZ_bDiBlDNqa-eT5g#scrollTo=Brp6iYWVNsKI

Note: Make sure to click 'Copy to Drive' to work out of your own Colab notebook.

This notebook focuses on **Qiskit Runtime**, a cloud-based service for efficient quantum circuit execution on IBM hardware.

##### **Summary:**
- **Setup**: Configure and connect to Qiskit Runtime services.
- **Backend Management**: Use the least busy backend for faster execution.
- **Execution**: Run circuits on real quantum hardware using Qiskit Runtime.

### 5. **theTranspiler(I3).ipynb**
https://colab.research.google.com/drive/1hZwz8LBoo3uVvndpA9o-pAv9R_pgGWHV#scrollTo=6c47ad18

Note: Make sure to click 'Copy to Drive' to work out of your own Colab notebook.

This notebook explores circuit optimization through Qiskit's transpiler, preparing circuits for hardware execution.

## **Additional Resources**

### **Official Documentation**
- [Qiskit Documentation](https://qiskit.org/documentation/)
- [IBM Quantum Learning](https://learning.quantum.ibm.com/)
- [Qiskit Textbook](https://qiskit.org/textbook/preface.html)

### **Development Tools**
- [Google Colab](https://colab.research.google.com/) - Cloud-based Python environment
- [IBM Quantum Lab](https://quantum-computing.ibm.com/) - Access to real quantum computers
- [Qiskit SDK GitHub](https://github.com/Qiskit/qiskit) - Source code and examples

### **Community Resources**
- [Qiskit Slack Community](https://qisk.it/join-slack)
- [Qiskit GitHub Discussions](https://github.com/Qiskit/qiskit/discussions)
- [Stack Exchange Q&A](https://quantumcomputing.stackexchange.com/questions/tagged/qiskit)

### **Learning Materials**
- [Coding with Qiskit YouTube Series](https://www.youtube.com/playlist?list=PLOFEBzvs-Vvp2xg9-POLJhQwtVktlYGbY)
- [Qiskit Summer School Materials](https://qiskit.org/events/summer-school/)
- [Quantum Computing Exercises](https://quantum-computing.ibm.com/lab/docs/iql/first-circuit)

##### **Summary:**
- **Optimization**: Use the transpiler to reduce gate depth and circuit size.
- **Comparison**: Test the impact of different transpiler settings.
- **Deployment**: Prepare circuits for noisy quantum hardware.

---

