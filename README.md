# Enhancing Image Restoration with Quantum-Integrated Contrastive Adversarial Networks

This repository contains the implementation of the research paper "Enhancing Image Restoration with Quantum-Integrated Contrastive Adversarial Networks" presented at IEEE INDISCON-2025. The model combines Contrastive Adversarial Networks (CANs) with Quantum Neural Networks (QNNs) using CUDA-Q for enhanced image restoration.

## Abstract
In this study, we present an advanced image enhancement model that synergistically combines contrastive adversarial networks (CANs) with quantum computing capabilities through quantum neural networks (QNNs) utilizing CUDA-Q. This innovative framework addresses the limitations of traditional image restoration techniques by employing quantum-enhanced feature extraction to capture intricate details within images. Furthermore, it leverages adversarial learning augmented by contrastive loss to yield high-quality restorations. Our model was evaluated on a set of 50 random photos from the CIFAR-10 dataset, achieving an average Structural Similarity Index Measure (SSIM) of 0.8873 and a Peak Signal-to-Noise Ratio (PSNR) of 22.5981. These results demonstrate significant enhancements over noisy baselines, with statistically considerable t-test findings (p < 0.0001). The integration of CUDA-Q accelerates computational efficiency, thereby reducing processing times while simultaneously improving the model’s capability to reconstruct fine details. This research highlights the transformative potential of quantum-enhanced machine learning in image restoration, laying the groundwork for future advancements in quantum-assisted computer vision.

## Key Features
- Hybrid quantum-classical architecture using PyTorch and CUDA-Q.
- Generator: U-Net style with residual connections and quantum-enhanced convolutions.
- Discriminator: PatchGAN-inspired with contrastive loss.
- Trained on Waterloo Exploration Database; tested on CIFAR-10.
- Metrics: SSIM (0.8873 avg), PSNR (22.5981 avg), with quantum integration for efficiency.


## Results
- Achieved SSIM: 0.8873 (avg), PSNR: 22.5981 (avg) on CIFAR-10 test set.
- Example outputs: See `figures/` for paper visuals or run inference to generate new ones.
- Statistical significance: p < 0.0001 over baselines.

# Acknowledgments
- Based on IEEE INDISCON-2025 presentation.
- Datasets: Waterloo Exploration Database, CIFAR-10.

