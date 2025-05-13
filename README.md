# Quantum Key Distribution (QKD) Implementation
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](QKDPROJECT_EBM.ipynb)

This repository contains a Jupyter notebook implementation of the BB84 quantum key distribution protocol using IBM's Qiskit package. The project demonstrates core quantum cryptography concepts through detailed code examples and explanations.

## Overview

Quantum Key Distribution (QKD) leverages quantum mechanical principles to establish secure communication channels between parties. This project focuses on the BB84 protocol, which:

- Uses quantum states to transmit information
- Provides security through the no-cloning theorem
- Enables detection of eavesdroppers

## Features

- Complete implementation of the BB84 protocol
- Simulation of eavesdropping detection
- Visualization of quantum circuits
- Detailed explanations of quantum cryptography concepts including:
  - Superposition
  - Measurement in different bases
  - The no-cloning theorem

## Requirements

The notebook requires the following Python packages:
- qiskit
- qiskit_aer
- numpy
- matplotlib
- random

## Usage

1. Clone this repository
2. Ensure all dependencies are installed
3. Open the Jupyter notebook `QKDPROJECT_EBM.ipynb`
4. Run the cells sequentially to see the QKD protocol in action

## Key Components

The implementation includes:
- Encoding quantum bits in random bases
- Simulating quantum transmission between Alice and Bob
- Introducing Eve as an eavesdropper
- Detecting eavesdropping through error rate analysis
- Privacy amplification techniques
- Visualization of quantum circuits using Qiskit

## Educational Value

This notebook serves as an educational resource for understanding:
- Fundamental principles of quantum cryptography
- How quantum properties can be leveraged for secure communication
- The threats posed by quantum computing to classical cryptography (via Shor's algorithm)
- Practical implementation of quantum protocols using Qiskit

## Background

This project was developed as part of undergraduate academic research into quantum cryptography at King's College London. It demonstrates how the unique properties of quantum mechanics can create cryptographic systems that are fundamentally different from classical approaches.

## Future Work

Potential extensions to this project include:
- Implementation of other QKD protocols (E91, B92)
- Quantum error correction
- Simulation of realistic noise models
- Comparison with classical cryptographic methods

## Author

Elliot B. Martindale
Email: elliotbmartindale@outlook.com

## Acknowledgements

This project builds upon the foundational work in quantum cryptography by Bennett and Brassard, and utilizes IBM's Qiskit framework for quantum simulations.
