# Data-Assisted Physics-Informed Neural Networks for the BBM Equation

This repository contains the official PyTorch implementation for the paper:

**"Error Decomposition and Stability Bounds for Data-Assisted PINNs: A Diagnostic Study of the Benjamin–Bona–Mahony Equation"**
*Authors: Jibrin Sale Yusuf, Aliyu Isa Aliyu, and Ado Balili*

## Overview
This code implements a data-assisted PINN for the Benjamin-Bona-Mahony (BBM) equation. The numerical experiments evaluate approximation accuracy through Sobolev errors, PDE residuals, and computational time, with a focus on network capacity, activation functions, collocation density, loss weighting, and optimization strategies. 

## Repository Structure
*   `PINN_BBM_Training.ipynb`: The main Jupyter Notebook containing the data generation, PINN architecture, training loop, and diagnostic experiments.
*   `requirements.txt`: List of required Python packages.

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/jsyusuf/PINN-BBM-Equation.git
   cd PINN-BBM-Equation
   ```
2. Install the dependencies:
      ```bash
      pip install -r requirements.txt
      ```
3. Launch Jupyter Notebook:
     ```bash
      jupyter notebook
      ```   
4. Open PINN_BBM_Training.ipynb and run the cells sequentially to reproduce the diagnostic results.
(Note: A CUDA-enabled GPU is highly recommended for training).
      

## Citation:
If you use this code in your research, please cite our paper:
```
@article{yusuf2026pinnbbm,
  title={Error Decomposition and Stability Bounds for Data-Assisted PINNs: A Diagnostic Study of the Benjamin-Bona-Mahony Equation},
  author={Yusuf, Jibrin Sale and Aliyu, Aliyu Isa and Balili, Ado},
  year={2026}
}
```
## License
This project is licensed under the MIT License.
