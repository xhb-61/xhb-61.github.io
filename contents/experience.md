### **Face Restoration with Reference Images**
**2026.05 - Present | Face Restoration · Reference-Guided Diffusion**

[[Project]](https://github.com/xhb-61/Face-restoration-with-reference-images)

Investigated reference-guided blind face restoration on heavily degraded concert-stage faces using Ref-LDM and FaceMe-inspired reference expansion.

#### Key Contributions

- Built a two-stage **GFPGAN + Ref-LDM img2img** restoration pipeline to improve LR structure preservation.
- Implemented FaceMe-style reference expansion with Arc2Face, ControlNet, and ArcFace identity filtering.
- Generated **162** same-identity reference images across 6 identities and restored all **22** LR face inputs.
- Ran CFG-scale sweeps and produced comparison sheets for systematic identity, structure, and artifact analysis.
- Diagnosed key failure modes including non-square resize distortion, weak noise2img structure constraints, unstable generated references, and reference-count limits.

---

### **Video Generation Deployment and Inference Optimization with AniSora**
**2026.03 - Present | Video Generation · Low-VRAM Inference**

[[Project]](https://github.com/xhb-61/AniSora-based-video-generation)

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

[[Project]](https://github.com/xhb-61/Controllable-Generation-via-Controlnet)

Explored conditional control mechanisms in diffusion models for character and face-oriented image generation.

#### Key Contributions

- Built inference pipelines with Hugging Face Diffusers and ControlNet pretrained models.
- Implemented depth-map and human-pose conditioned generation.
- Evaluated edge, pose, sketch, and semantic-segmentation controls.
- Summarized how different control signals affect stability, constraint strength, and generation quality.

---

### **Blind Image Deblurring with Deep Tensor Low-Rank Priors**
**2025.06 - Present | Self-Supervised Restoration · Tensor Low-Rank Regularization**

[[Project]](https://github.com/xhb-61/Blind-Image-Deblurring-with-Deep-Tensor-Low-Rank-Priors)

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
