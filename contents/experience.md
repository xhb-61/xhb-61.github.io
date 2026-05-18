### **Video Generation Deployment and Inference Optimization with AniSora**
**2026.03 - Present | Video Generation · Low-VRAM Inference**

Deployed and validated a low-VRAM AniSora inference workflow on Linux multi-GPU servers for video generation experiments.

#### Key Contributions

- Analyzed the inference package structure, quantization path, and dependency chain.
- Built a minimal runnable path with PyTorch fallback.
- Designed inference experiments with offload and lazy-loading strategies under 12GB VRAM constraints.
- Generated single-sample and batch-sample demos, including 3s/6s videos and 320p/480p configurations.
- Compared generation quality, temporal consistency, and memory cost across 3s/6s, 320p/1-step, and 480p/4-step settings.

---

### **Controllable Generation with ControlNet**
**2026.01 - Present | Diffusion Models · ControlNet · Diffusers**

Explored conditional control mechanisms in diffusion models for character and face-oriented image generation.

#### Key Contributions

- Built inference pipelines with Hugging Face Diffusers and ControlNet pretrained models.
- Implemented depth-map and human-pose conditioned generation.
- Evaluated edge, pose, sketch, and semantic-segmentation controls.
- Summarized how different control signals affect stability, constraint strength, and generation quality.

---

### **Blind Image Deblurring with Deep Tensor Low-Rank Priors**
**2025.06 - Present | Self-Supervised Restoration · Tensor Low-Rank Regularization**

Developed a self-supervised blind deblurring framework that combines deep image priors with tensor low-rank regularization for complex non-uniform blur restoration.

#### Key Contributions

- Built a deep self-supervised network for image feature extraction and blur-kernel estimation.
- Introduced tensor low-rank regularization as a global constraint to stabilize optimization.
- Improved PSNR by **0.44 dB** on the Lai non-uniform blur benchmark compared with strong baselines.

---

### **Efficient Image Restoration with Plug-and-Play Priors**
**2023.06 - 2025.05 | Inverse Problems · PnP Priors · Convergence Guarantees**

Worked on a modular plug-and-play restoration framework for mixed-noise image recovery with both practical performance and theoretical stability.

#### Key Contributions

- Designed optimization algorithms for mixed-noise characteristics.
- Trained deep denoising models under different noise levels.
- Contributed to cocoercive denoisers with convergence-aware restoration behavior.
- Related works accepted by **NeurIPS 2025** and **Numerical Algorithms**.
