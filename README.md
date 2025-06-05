# Entangled Structure Compression and Symbolic Entropy Experiments

This repository contains the code and simulations supporting the paper:

"Entangled Structure Compression of Quantum Volumetric States: A Unitary Framework for Pattern Detection and Symbolic Encoding"  
*Submitted to Physical Review A (PRA), 2025*  
Author: Mohammadreza Safaie  
ORCID: [0000-0002-6980-0044](https://orcid.org/0000-0002-6980-0044)  
Email: mohammadreza.safaie.qm@gmail.com

## Overview

This repository includes the core quantum and symbolic simulations that demonstrate key aspects of the compression framework proposed in the paper. The main focus is on:

- GHZ + SWAP test implemented in Cirq to verify entangled pattern similarity.
- Advanced SWAP test to detect mismatches between entangled GHZ states.
- Symbolic pattern compression and entropy analysis, implemented using PyTorch/Numpy, which computes symbolic IDs for binary voxel-like structures and evaluates symbolic entropy (S_ent) based on identifier distributions.

## Repository Structure
├── ghz_swap_test_basic.ipynb          # Cirq-based GHZ state SWAP test ├── ghz_swap_test_advanced.ipynb       # Mismatch-sensitive SWAP test ├── symbolic_entropy_simulation.ipynb  # Symbolic ID + entropy simulation ├── symbolic_entropy_plot.png          # Output plot (Figure 1 in paper) ├── README.md                          # This file

## Instructions

All simulations were tested on [Google Colab](https://colab.research.google.com).  
No setup is needed — just open each .ipynb file and run the cells sequentially.  
You may optionally install locally:
`bash
pip install cirq matplotlib numpy torch
