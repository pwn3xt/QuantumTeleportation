# Quantum Teleportation Protocol with Qiskit
<img src="https://media.giphy.com/media/cW55zyF7dJAf6/giphy.gif"/>

This repository contains two quantum circuits implemented using [Qiskit](https://www.ibm.com/quantum/qiskit) . The circuits demonstrate basic quantum entanglement, which is employed as a fundamental component in the second quantum teleportation circuit. 


## Circuits

1. **Entanglement Circuit (`bellPair_prep.ipynb`):**
   - Establishes an entangled state between two qubits for Alice and one qubit for Bob.
   - Utilizes Hadamard and controlled-X gates to create quantum entanglement.
   - Measures and simulates the outcomes using Qiskit's quantum simulator.
   ![image](https://github.com/pwn3xt/QuantumTeleportation/assets/62956414/3497c8b6-8da3-4e4d-b2c2-1c7a5cdfaf68)

2. **Quantum Teleportation Circuit (`teleportation.ipynb`):**
   - Expands on entanglement with additional Quantum Teleportation Circuit.
   - Includes single-qubit rotations, controlled gates, and measurements.
   - Visualized with barriers for a clear representation of the quantum circuit.
   ![image](https://github.com/pwn3xt/QuantumTeleportation/assets/62956414/e8068178-13bd-4538-ae30-7c1acd0f68c2)


We also executed these circuits on real quantum hardware using the [IBM Quantum Experience website](https://quantum.ibm.com/) for a hands-on exploration of quantum computing.

## Acknowledgments

- This project was developed as part of a team project for the CSE454s Quantum Communication and Security subject at Ain Shams University. The ohter parts can be found [here](https://github.com/0ssamaak0/QuanTorch) and [here](https://colab.research.google.com/drive/1mag2zSY_rgxOaHDJjdLGtUfQIftdSBOr#scrollTo=OrFkt6FGcheg)
- The circuits are implemented using Qiskit, an open-source quantum computing framework developed by IBM. For more details on Qiskit, refer to the official Qiskit [Documentation](https://docs.quantum.ibm.com/).

