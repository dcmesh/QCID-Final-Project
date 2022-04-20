# QCID-Final-Project
Group final project for CSDS/MATH/PHYS 486: Quantum Computing, Information, and Devices at Case Western Reserve University

-------

## QAE Simulation 1

By: David Meshnick

Based on: [Quantum autoencoders with enhanced data encoding](https://arxiv.org/abs/2010.06599)

Relevant Files:
- qae.py
- ./plots
- ./Lit/qae_enhanced.pdf

Work:
- Implemented base quantum autoencoder (QAE) and feature-enhanced quantum autoencoder (EF_QAE) using `qibo` backend
- Simulated cost function on Ising model and MNIST dataset

Run:

`python QADsim/qae.py --layers 3 --example 0`
- `--layers <int>`: How many layers the autoencoder should have
- `--example <int>`: Which example to test. `0` for Ising, `1` for MNIST
-----

## QAE Simulation 2

By: David Meshnick

Based on: [Variational quantum anomaly detection: Unsupervised mapping of phase diagrams on a physical quantum computer](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.043184)

Relevant Files:
- utils.py
- qae_simulation.ipynb
- ./Lit/vqad_phase.pdf

Work:
- Implemented EF_QAE from Simulation 1 with the [qiskit](https://qiskit.org/) backend
- Demonstrated functionality and verified results of the source literature

Run:

Open the jupyter notebook and execute the cells
