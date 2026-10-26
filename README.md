# Foundation models for PDEs in fluid dynamics

David Nelischer · M2 Physics of Complex Systems, Université Paris-Saclay · 2025

Master's thesis carried out at the Seminar for Applied Mathematics, ETH Zürich,
under the supervision of Prof. Siddhartha Mishra.

This thesis investigates contrastive representation learning for PDE solution
operators within the POSEIDON framework. My work adapts Rank-N-Contrast to the
scalable operator transformer (scOT), combining a contrastive objective with a
reconstruction loss. Experiments on the wave equation and incompressible
Navier–Stokes equations compare this approach with standard regression training,
including evaluation on unseen initial-condition distributions.

## Documents

- [Thesis report](thesis.pdf) — June 2025.
- [Presentation slides](presentation.pdf) — July 2025.

This repository contains the report and slides; implementation code is not included.

## References

- Maximilian Herde et al. [Poseidon: Efficient Foundation Models for PDEs](https://arxiv.org/abs/2405.19101). NeurIPS, 2024.
- Kaiwen Zha et al. [Rank-N-Contrast: Learning Continuous Representations for Regression](https://arxiv.org/abs/2210.01189). NeurIPS, 2023.
