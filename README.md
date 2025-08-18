# PfA-SNN

Parameter-free Attention (PfA) for Spiking Neural Networks with a complete CIFAR-10 example.  
The core module is implemented as `atten_pfa()`, which you can drop into other frameworks with minimal changes.

---

## Overview
- **What it is:** A parameter-free attention mechanism for SNNs.
- **Where it plugs in:** Directly after the **input current** \(the weighted sum of spikes, \(I\)\).
- **Parameter-free:** No extra learnable parameters and no need to build an extra loss function.
- **Frameworks:** Implemented in **PyTorch** with **SpikingJelly**; easy to port elsewhere.

For the methodology, see the paper: [Neural Networks, 2025](https://www.sciencedirect.com/science/article/pii/S0893608025000334).

---

## Requirements
- Python 
- [PyTorch](https://pytorch.org/)
- [SpikingJelly](https://github.com/fangwei123456/spikingjelly)


