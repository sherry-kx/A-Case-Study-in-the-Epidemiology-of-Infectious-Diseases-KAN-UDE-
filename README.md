# A Case Study in the Epidemiology of Infectious Diseases: KAN-UDE

This repository contains the complete implementation code for our comparative study on neural network-based methods (MLP, KAN, and KAN-UDE) applied to the simulation and prediction of infectious disease dynamics using compartment models.

## Project Structure

The code is organized into two main experimental settings: `A` and `R`, each of which includes:
 `A` and `R` respectively indicate whether the data used are newly infected cases or daily reported cases.
- `MLPVSKAN/` – Comparative analysis between MLP and KAN.
- `mlp$KAN/` – Performance testing and plotting for various hidden units (5, 8, 16, 32, 64, 128).
- `Noisy/` – Experimentation on noisy datasets (with compartment subfolders like `E`, `SI`, `fenshi`, and `t`).
- `prediction/` – Inference results using trained models, with multiple input scenarios (`in_YC_A_*.tif`).

Each subfolder typically contains:
- `.   ipynb` notebooks for training, simulation, and plotting.
- `.tif` images for visual comparison.
- Subfolders such as `result/`, `picture/`, and `figure/` for intermediate and final visual outputs.
