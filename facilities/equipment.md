
# IWU Computational Chemistry Cluster – *Sisyphus*

This document provides an overview of the **Sisyphus** cluster used by the IWU Chemistry department.

---
title: Teaching and Research Equipment
layout: page

## 🔧 System Overview

| | Description |
|-------------------|----------------------------------------------------------|
| **Operating System** | Ubuntu 24.04 LTS |
| **Scheduler** | SLURM | |
| **Storage** | `/home` (NFS), `/scratch` (local scratch on worknodes) |

---

## 💻 Worker Node Specifications

| Node Name | CPU Model | Cores | RAM | Dedicated GPU | Notes |
|---------------|-------------------|-------|-------|---|--------------------------|
| `worknode[1-2]` | 2x AMD EPYC 7543 | 64 | 1TB | None | CPUs treated as consumable resource by slurm
|`Puget1` | Intel Xeon E5-2630 | 32 | 128GB | NVIDIA GeForce GTX 980 | coming online soon |
| `Puget2` | Intel Core i9 7980XE | 18 | 96GB |NVIDIA Titan Xp 12GB| coming online soon



---

## 📦 Available Software

| Software | Version(s) | Description |
|----------------|----------------|----------------------------------------|
| PSI4 | nightly GitHub build | Quantum chemistry |
| Gaussian | 2016 | Quantum Chemistry (restricted access) |
| Molpro | 2024 | Quantum Chemistry |
| NAMD | 3.0 | Molecular Dynamics |
| VMD | 2.0 | Molecular Dynamics Visualization |





---

## 📞 Contact

For access requests, issues, or help using the cluster, contact:
**Dr. Nate Kitzmiller** nate.kitzmiller@indwes.edu*

---

_Last updated: May 2025_
