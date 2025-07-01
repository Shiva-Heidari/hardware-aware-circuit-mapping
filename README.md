# Hardware-Aware Circuit Mapping with Qiskit

This project demonstrates how quantum circuits are transpiled for specific hardware backends using **Qiskit**, taking into account real device topologies and optimization strategies. It visually and numerically compares the effects of different transpilation levels on circuit layout and depth for both real IBM backends and simulated (fake) devices.

## Key Concepts

- **Hardware-aware transpilation**: Adapting logical circuits to physical constraints of quantum hardware.
- **Optimization levels**: Comparing low (0) and high (3) optimization strategies in Qiskit.
- **Circuit layout visualization**: Showing how logical qubits are mapped onto physical qubits.
- **Fake backends**: Using Qiskit’s simulated IBMQ devices for educational/demo purposes.

## Notebook Included

- [`hardware_aware_circuit_mapping.ipynb`](hardware_aware_circuit_mapping.ipynb):  
  A complete walkthrough demonstrating:
  - A 4-qubit GHZ-like state creation
  - Transpilation for `FakeYorktown` and `FakeAthens`
  - Layout visualization with `plot_circuit_layout`
  - Discussion of qubit connectivity and circuit depth changes

