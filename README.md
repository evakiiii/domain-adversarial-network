Dynamic and Robust Domain Adversarial Network (DRDAN)

A Novel Framework for Sensor Drift Compensation in Artificial Olfactory Systems

This repository provides the official PyTorch implementation of the DRDAN framework, as presented in our paper. DRDAN addresses the critical challenge of sensor drift in artificial olfactory systems (AOS) by integrating adversarial domain adaptation with confidence-weighted ensemble learning.

Sensor drift—caused by environmental interference, sensor aging, and batch-to-batch variation—severely degrades the long-term performance of AOS. DRDAN is designed to:

Learn domain-invariant feature representations through global-local adversarial discriminators and class-discriminative constraints.

Enhance prediction robustness via a dynamically weighted ensemble mechanism that adapts to drifting data distributions.

Achieve state-of-the-art performance in cross-domain gas recognition tasks under complex drift scenarios.




If you find this code useful in your research, please consider citing our paper:

bibtex
@article{
  title={Domain adversarial network with dynamic joint adaptation and robust ensemble learning for drift compensation of artificial olfactory system},
  journal={Microchemical Journal},
  year={2025}
}
