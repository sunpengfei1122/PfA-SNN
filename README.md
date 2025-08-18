# PfA-SNN

Parameter-free Attention (PfA) for Spiking Neural Networks with a complete CIFAR-10 example.  
The core module is implemented as `atten_pfa()`, which you can drop into other frameworks with minimal changes. For the spiking fully-connected layer (Usually utilized in spiking audio datasets, like SHD and SSC), you can set the height (H)  to the number of hidden neurons and the width (W) to 1.

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

## **Paper Details:**

[<button>PDF</button>](https://www.sciencedirect.com/science/article/pii/S0893608025000334)  
<button onclick="showBibtex('bib1')">Cite</button>

<div id="bib1" style="display:none; position:fixed; top:20%; left:50%; transform:translateX(-50%); background:#fff; border:1px solid #ccc; padding:1em; z-index:100; max-width:600px;">
  <pre id="txt1" style="white-space:pre-wrap;">
@ARTICLE{sun2025parameterfree,
  author={Sun, Pengfei and Wu, Jibin and Devos, Paul and Botteldooren, Dick},
  title={Towards parameter-free attentional spiking neural networks},
  journal={Neural Networks},
  year={2025},
  volume={185},
  pages={107154},
  doi={10.1016/j.neunet.2025.107154}}
  </pre>
</div>



