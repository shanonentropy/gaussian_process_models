# Gaussian Process Models for NV Sensing

## Overview
Exploring GP models to map NV ODMR and PL spectra onto thermodynamic variables of interest.
Published results show GP with Matérn kernel captures ODMR spectra well, mapping to temperature with uncertainty < 1K.

## Data
- ODMR/ESR data: `./nv_odmr/`
- PL data: `./pl_data/`
- Experiments: `./gaussian_process_models/`

## Roadmap

### 1. ODMR Spectra Modeling
- [ ] Test different kernels for ODMR spectra
- [ ] Sparse GP for ODMR spectra

### 2. PL Spectra Modeling
- [ ] Expand to PL spectra with RQ and RBF kernels
- [ ] Sparse GP for PL spectra

### 3. Latent Representation & Fusion
- [ ] Learn latent representations of ODMR and PL data
- [ ] Fuse GP output with deep learning activations
- [ ] Fuse ODMR and PL using Kalman filters (on model output)
- [ ] Fuse ODMR and PL using Kalman filters (on latent output)

## Benchmarking
- Compare GP fusion vs neural network based fusion

 
