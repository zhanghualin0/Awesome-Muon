# Awesome Muon[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo collects papers, documents, and code about the Muon optimizer for anyone who wants to research it. Status labels were refreshed on June 3, 2026 from public OpenReview, arXiv, conference pages, and title/abstract searches around Muon, LMO, linear minimization oracle, spectral descent, orthogonal optimizers, and matrix-sign methods. Tables are sorted descending by latest arXiv version date; conference-only rows use the status refresh date. Dates shown next to `arXiv` labels are the latest arXiv version dates. `arXiv` means no newer peer-reviewed venue status was found in this pass. ★ indicates accepted papers, and ⭐ indicates a citation count exceeding 5.

## Table of Contents

- [Papers](#papers)
  - [2026](#2026)
  - [2025](#2025)
  - [2024](#2024)

## Papers

### 2026

| Status | Title | Keywords |
| --- | --- | --- |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | Can Muon Fine-tune Adam-Pretrained Models? | Adam pretraining, Muon fine-tuning, optimizer switching, loss landscape, transfer |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | General Analysis of LMO-based Optimizers: Beyond Bounded Variance | LMO-based optimizers, beyond bounded variance, convergence theory, stochastic optimization, Muon family |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | MuonSSM: Orthogonalizing State Space Models for Sequence Modeling | state space models, sequence modeling, orthogonalization, ICML 2026, Muon |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | Non-Euclidean Gradient Descent Operates at the Edge of Stability | edge of stability, non-Euclidean descent, Muon, Shampoo, optimizer dynamics |
| ★ [ICML 2026 Spotlight](https://zichongli5.github.io/) | NorMuon: Making Muon more efficient and scalable [[OpenReview](https://openreview.net/forum?id=7TeJXgr7L6)] | neuron-wise normalization, adaptive learning rates, FSDP2, LLM pretraining, scalability |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | Spectra: Rethinking Optimizers for LLMs Under Spectral Anisotropy | spectral anisotropy, LLM optimizers, layer geometry, adaptive updates, training dynamics |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | Spectral Gradient Descent Mitigates Anisotropy-Driven Misalignment in Low-Rank Matrix Factorization | spectral gradient descent, anisotropy, low-rank factorization, misalignment, implicit regularization |
| [arXiv 2026-06-02](https://arxiv.org/abs/2605.18106) | Symmetry-Compatible Principle for Optimizer Design: Embeddings, LM Heads, SwiGLU MLPs, and MoE Routers | symmetry-compatible optimizers, equivariance, Scion, Muon, MoE routers |
| [arXiv 2026-05-29](https://arxiv.org/abs/2605.26929) | When Muon Optimizer Meets Adversarial Training: A Theoretical and Empirical Study | adversarial training, robustness, Muon theory, optimization dynamics, empirical study |
| [arXiv 2026-05-26](https://arxiv.org/abs/2605.26842) | MONA: Muon Optimizer with Nesterov Acceleration for Scalable Language Model Training | Nesterov acceleration, curvature-aware updates, MoE pretraining, MONA-Lite, sharp minima |
| ★ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2026-05-25](https://arxiv.org/abs/2602.05725) | Muon in Associative Memory Learning: Training Dynamics and Scaling Laws | associative memory, scaling laws, long-tail frequencies, matrix sign, theory |
| ★ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2026-05-24](https://arxiv.org/abs/2602.16340) | The Implicit Bias of Adam and Muon on Smooth Homogeneous Neural Networks | implicit bias, homogeneous networks, margin maximization, Adam, spectral norm |
| [arXiv 2026-05-23](https://arxiv.org/abs/2605.24770) | Muon in Vision Transformers | vision transformers, image classification, optimizer transfer, scaling, architecture study |
| [arXiv 2026-05-22](https://arxiv.org/abs/2605.23871) | Move on Muon: The Trajectory of Landscape Optimization | training trajectories, loss landscape, optimizer dynamics, Muon analysis, geometry |
| [arXiv 2026-05-21](https://arxiv.org/abs/2605.22432) | AMUSE: Anytime Muon with Stable Gradient Evaluation | schedule-free training, stable averaging, river-valley landscape, anytime optimization, Muon |
| [arXiv 2026-05-21](https://arxiv.org/abs/2603.10067) | HTMuon: Improving Muon via Heavy-Tailed Spectral Correction | heavy-tailed spectra, Schatten norm, spectral correction, LLM pretraining, generalization |
| [arXiv 2026-05-19](https://arxiv.org/abs/2605.19781) | From SGD to Muon: Adaptive Optimization via Schatten-p Norms | Schatten-p norms, SGD-Muon interpolation, adaptive optimization, spectral geometry, matrix updates |
| [arXiv 2026-05-18](https://arxiv.org/abs/2605.18174) | Ringmaster LMO: Asynchronous Linear Minimization Oracle Momentum Method | asynchronous optimization, LMO momentum, distributed training, system heterogeneity, NanoChat |
| [arXiv 2026-05-14](https://arxiv.org/abs/2602.21545) | Muon+: Towards Better Muon via One Additional Normalization Step | post-orthogonalization normalization, perplexity, LLaMA, GPT, simplicity |
| [arXiv 2026-05-12](https://arxiv.org/abs/2605.11396) | MuonQ: Enhancing Low-Bit Muon Quantization via Directional Fidelity Optimization | 4-bit optimizer state, directional fidelity, companding, quantization, memory efficiency |
| [arXiv 2026-05-11](https://arxiv.org/abs/2605.11181) | Muon is Not That Special: Random or Inverted Spectra Work Just as Well | Freon, Kaon, LMO critique, Schatten quasi-norms, step-size optimality |
| [arXiv 2026-05-11](https://arxiv.org/abs/2605.10797) | Muown: Row-Norm Control for Muon Optimization | row-norm control, spectral norm drift, weight decay sensitivity, pretraining, stability |
| [arXiv 2026-05-11](https://arxiv.org/abs/2605.11172) | Optimistic Dual Averaging Unifies Modern Optimizers: Muon, AdEMAMix, and AdamW | dual averaging, optimizer unification, AdamW, AdEMAMix, Muon theory |
| [arXiv 2026-05-10](https://arxiv.org/abs/2605.09238) | Intrinsic Muon: Spectral Optimization on Riemannian Matrix Manifolds | iMuon, Riemannian manifolds, intrinsic LMO, fixed-rank matrices, symmetry preservation |
| [arXiv 2026-05-10](https://arxiv.org/abs/2603.28254) | MuonEq: Balancing Before Orthogonalization with Lightweight Equilibration | pre-orthogonalization equilibration, row-column normalization, LLaMA pretraining, Muon variants, convergence |
| [arXiv 2026-05-09](https://arxiv.org/abs/2605.08980) | Muon Does Not Converge on Convex Lipschitz Functions | convergence counterexample, convex optimization, Lipschitz losses, theory, limitations |
| [arXiv 2026-05-07](https://arxiv.org/abs/2605.05577) | Accelerating LMO-Based Optimization via Implicit Gradient Transport | LMO-IGT, implicit gradient transport, Muon-IGT, variance reduction, convergence |
| [arXiv 2026-05-06](https://arxiv.org/abs/2605.04418) | Demystifying Manifold Constraints in LLM Pre-training | MACRO, manifold constraints, Riemannian LMO, normalization-free training, weight decay |
| [arXiv 2026-04-11](https://arxiv.org/abs/2604.09967) | Muon$^2$: Boosting Muon via Adaptive Second-Moment Preconditioning | second moments, preconditioning, Newton-Schulz efficiency, LLM pretraining, factorization |
| [arXiv 2026-04-01](https://arxiv.org/abs/2604.01472) | The Newton-Muon Optimizer | Newton-type optimizer, activation preconditioning, quadratic surrogate, Modded-NanoGPT, curvature |
| [arXiv 2026-03-18](https://arxiv.org/abs/2603.17970) | Beyond Muon: MomentUm Decorrelation | momentum decorrelation, optimizer variants, spectral updates, LLM pretraining, Muon alternatives |
| ★ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2026-03-05](https://arxiv.org/abs/2601.08393) | Controlled LLM Training on Spectral Sphere | spectral sphere optimizer, muP alignment, activation stability, weight constraints, LLM pretraining |
| [arXiv 2026-03-04](https://arxiv.org/abs/2603.03597) | NuMuon: Nuclear-Norm-Constrained Muon for Compressible LLM Training | nuclear norm, low-rank bias, LLM compression, compressible weights, Muon variant |
| [arXiv 2026-02-20](https://arxiv.org/abs/2602.17080) | Adam Improves Muon: Adaptive Moment Estimation with Orthogonalized Momentum | NAMO, adaptive moments, orthogonalized momentum, stochastic noise, GPT pretraining |
| [arXiv 2026-02-10](https://arxiv.org/abs/2602.09314) | Clarifying Shampoo: Adapting Spectral Descent to Stochasticity and the Parameter Trajectory | Shampoo, spectral descent, adapted Muon update, token efficiency, stochasticity |
| ★ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2026-02-04](https://arxiv.org/abs/2602.04669) | Delving into Muon and Beyond: Deep Analysis and Extensions | spectral transforms, RMS normalization, optimizer analysis, Adam comparison, Muon variants |
| [arXiv 2026-02-03](https://arxiv.org/abs/2602.03001) | Adaptive Batch Sizes Using Non-Euclidean Gradient Noise Scales for Stochastic Sign and Spectral Descent | gradient noise scale, adaptive batch size, spectral descent, Signum, Muon |
| [arXiv 2026-01-30](https://arxiv.org/abs/2601.23000) | Mano: Restriking Manifold Optimization for LLM Training | oblique manifold, tangent momentum, LLM optimizer, AdamW comparison, Muon comparison |
| [arXiv 2026-01-29](https://arxiv.org/abs/2601.21487) | Manifold constrained steepest descent | MCSD, LMO, Riemannian gradient, Stiefel manifold, SPEL |
| [arXiv 2026-01-21](https://arxiv.org/abs/2601.14603) | Variance-Adaptive Muon: Accelerating LLM Pretraining with NSR-Modulated and Variance-Scaled Momentum | variance adaptation, NSR modulation, Muon-VS, LLM pretraining, convergence speed |
| [arXiv 2026-01-20](https://arxiv.org/abs/2601.13474) | Preconditioning Benefits of Spectral Orthogonalization in Muon | matrix factorization, in-context learning, spectral preconditioning, linear convergence, theory |

### 2025

| Status | Title | Keywords |
| --- | --- | --- |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=g2l9bg9DWx) | Achieving low-bit Muon through subspace preservation and grid quantization | low-bit training, grid quantization, subspace preservation, 4-bit Muon, memory |
| ★ ⭐ [ICLR 2026 Poster](https://openreview.net/forum?id=OpxVAHFmkL) | AdaMuon: Adaptive Muon Optimizer | adaptive scaling, second momentum, sign-stabilized update, RMS alignment, LLM pretraining |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | An Exploration of Non-Euclidean Gradient Descent: Muon and its Many Variants | non-Euclidean descent, optimizer variants, geometry, Muon, theory |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=lJSfxtLpLm) | Convergence of Muon with Newton-Schulz | Newton-Schulz, convergence theory, polar factor, nonconvex optimization, rank dependence |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=rex7s82Iav) | Error Feedback for Muon and Friends | error feedback, distributed optimization, compression, non-Euclidean LMO, communication |
| ★ ⭐ [ICLR 2026 Poster](https://openreview.net/forum?id=2J51qUZ0iG) | Fantastic Pretraining Optimizers and Where to Find Them | optimizer benchmarking, LLM pretraining, hyperparameter tuning, matrix optimizers, scaling |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=9k7bvBVenZ) | FedMuon: Federated Learning with Bias-corrected LMO-based Optimization | bias correction, LMO, federated optimization, Newton-Schulz, convergence |
| ★ [NeurIPS](https://openreview.net/forum?id=Ei6IsmxYrb) | How to Scale Second-Order Optimization | second-order optimization, scaling, preconditioning, large models, training efficiency |
| ★ [ICML 2026](https://icml.cc/Downloads/2026) | LiMuon: Light and Fast Muon Optimizer for Large Models | lightweight optimizer, fast Muon, large models, efficiency, ICML 2026 |
| ★ ⭐ [ICML 2026](https://icml.cc/Downloads/2026) | Lions and Muons: Optimization via Stochastic Frank-Wolfe | stochastic Frank-Wolfe, constrained optimization, Lion, Muon, theory |
| [Submitted to ICLR 2026](https://openreview.net/forum?id=go388T3QjQ) | Long-tailed Learning with Muon Optimizer | long-tailed recognition, sharp minima, negative curvature, ProMO, imbalanced data |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=WtbXgc9GVA) | LoRA meets Riemannion: Muon Optimizer for Parametrization-independent Low-Rank Adapters | LoRA, Riemannian optimization, fixed-rank manifold, adapters, fine-tuning |
| ★ ⭐ [Accepted by TMLR](https://openreview.net/forum?id=Blz4hjxLwU) | Muon Optimizes Under Spectral Norm Constraints | spectral norm constraints, implicit regularization, Lion-K, TMLR, theory |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=twbMFL0DMp) | Muon Outperforms Adam in Tail-End Associative Memory Learning | associative memory, tail classes, heavy-tailed data, isotropic spectra, ICLR 2026 |
| ★ [NeurIPS ER Workshop](https://openreview.net/forum?id=NHM0lL832y) | Muon: Training and Trade-offs with Latent Attention and MoE | latent attention, mixture-of-experts, trade-offs, optimizer evaluation, training recipes |
| ★ [ICLR 2026 Poster](https://openreview.net/forum?id=mHouLSUQP5) | MuonBP: Faster Muon via Block-Periodic Orthogonalization | block-periodic orthogonalization, tensor parallelism, throughput, distributed training, convergence |
| [Submitted to ICLR 2026](https://openreview.net/forum?id=TpxkCwftHF) | On quantizing the state of the Muon optimizer [[SPOT](https://openreview.net/submissions?venue=ICLR.cc%2F2026%2FWorkshop%2FSPOT)] | 8-bit Muon, optimizer states, blockwise quantization, memory footprint, LLMs |
| ⭐ [Submitted to ICLR 2026](https://openreview.net/forum?id=CPhda7grEo) | On the Convergence of Muon and Beyond | variance reduction, nonconvex convergence, Muon-MVR, PL condition, stochastic optimization |
| ★ [Proceedings of the First BabyLM Workshop](https://aclanthology.org/2025.babylm-main.14/) | Sample-Efficient Language Modeling with Linear Attention and Lightweight Enhancements | BabyLM, linear attention, sample efficiency, lightweight training, language modeling |
| ★ ⭐ [ICLR 2026 Oral](https://openreview.net/forum?id=yRtgZ1K8hO) | The Polar Express: Optimal Matrix Sign Methods and Their Application to the Muon Algorithm | matrix sign, polar decomposition, optimal polynomials, Newton-Schulz, GPU efficiency |
| ★ [High-dimensional Learning Dynamics at ICML Poster](https://openreview.net/forum?id=ppmyFtr9EW) | Towards Understanding Orthogonalization in Muon [[code](https://anonymous.4open.science/r/MuonSBW-23A2)] | orthogonalization, learning dynamics, spectral bias, theory, Muon mechanics |
| [arXiv 2026-06-02](https://arxiv.org/abs/2510.01377) | DeMuon: A Decentralized Muon for Matrix Optimization over Graphs | decentralized optimization, graph networks, matrix optimization, Muon, distributed algorithms |
| ★ ⭐ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2026-06-02](https://arxiv.org/abs/2505.23725) | MuLoCo: Muon is a practical inner optimizer for DiLoCo | DiLoCo, distributed training, communication efficiency, inner optimizer, LLMs |
| [arXiv 2026-05-20](https://arxiv.org/abs/2506.16659) | A Minimalist Optimizer Design for LLM Pretraining | minimalist optimizer, LLM pretraining, training recipes, efficiency, optimizer design |
| [arXiv 2026-05-20](https://arxiv.org/abs/2505.24275) | GradPower: Powering Gradients for Faster Language Model Pre-Training | gradient powers, pretraining speed, language models, optimizer variant, matrix updates |
| [arXiv 2026-04-19](https://arxiv.org/abs/2509.11983) | Low-rank Orthogonalization for Large-scale Matrix Optimization with Applications to Foundation Model Training | low-rank orthogonalization, matrix optimization, foundation models, scalability, training |
| [arXiv 2026-04-19](https://arxiv.org/abs/2510.09378) | The Potential of Second-Order Optimization for LLMs: A Study with Full Gauss-Newton | Gauss-Newton, second-order optimization, LLMs, scalability, optimizer comparison |
| [arXiv 2026-03-16](https://arxiv.org/abs/2509.25164) | YOLO26: Key Architectural Enhancements and Performance Benchmarking for Real-Time Object Detection | object detection, YOLO, benchmarking, real-time inference, optimizer application |
| [arXiv 2026-03-01](https://arxiv.org/abs/2510.21314) | A Convergence Analysis of Adaptive Optimizers under Floating-point Quantization | floating-point quantization, adaptive optimizers, convergence, numerical precision, training stability |
| [arXiv 2026-02-24](https://arxiv.org/abs/2506.10935) | Accelerating Newton-Schulz Iteration for Orthogonalization via Chebyshev-type Polynomials | Newton-Schulz, Chebyshev polynomials, orthogonalization, numerical linear algebra, acceleration |
| [arXiv 2026-02-22](https://arxiv.org/abs/2509.23106) | Effective Quantization of Muon Optimizer States | optimizer-state quantization, low-bit Muon, memory reduction, training stability, LLMs |
| [arXiv 2026-02-03](https://arxiv.org/abs/2507.20534) | Kimi K2: Open Agentic Intelligence | open model, agentic intelligence, large-scale pretraining, Muon application, model report |
| [arXiv 2026-02-02](https://arxiv.org/abs/2510.14009) | Noise-Adaptive Layerwise Learning Rates: Accelerating Geometry-Aware Optimization for Deep Neural Network Training | layerwise rates, noise adaptation, geometry-aware optimization, acceleration, deep networks |
| [arXiv 2026-01-29](https://arxiv.org/abs/2510.21800) | MARS-M: When Variance Reduction Meets Matrices | variance reduction, matrix optimizers, training efficiency, stochastic optimization, Muon family |
| [arXiv 2025-12-18](https://arxiv.org/abs/2509.24320) | AuON: A Linear-time Alternative to Semi-Orthogonal Momentum Updates | linear-time optimizer, semi-orthogonal updates, momentum, scalability, Muon alternative |
| [arXiv 2025-12-15](https://arxiv.org/abs/2507.07101) | Small Batch Size Training for Language Models: When Vanilla SGD Works, and Why Gradient Accumulation Is Wasteful | small batch training, SGD, gradient accumulation, language models, optimizer comparison |
| [arXiv 2025-12-12](https://arxiv.org/abs/2510.22980) | How Muon's Spectral Design Benefits Generalization: A Study on Imbalanced Data | spectral design, generalization, imbalanced data, tail classes, Muon analysis |
| [arXiv 2025-12-05](https://arxiv.org/abs/2502.04664) | Implicit Bias of Spectral Descent and Muon on Multiclass Separable Data | implicit bias, multiclass classification, spectral descent, margin maximization, theory |
| [arXiv 2025-12-04](https://arxiv.org/abs/2512.04632) | Turbo-Muon: Accelerating Orthogonality-Based Optimization with Pre-Conditioning | preconditioning, Newton-Schulz speedup, orthogonality, runtime, drop-in Muon |
| [arXiv 2025-11-21](https://arxiv.org/abs/2507.01598) | Convergence Bound and Critical Batch Size of Muon Optimizer | critical batch size, convergence bound, scaling, stochastic optimization, Muon theory |
| [arXiv 2025-11-06](https://arxiv.org/abs/2511.04456) | Federated Stochastic Minimax Optimization under Heavy-Tailed Noises | federated learning, minimax optimization, heavy-tailed noise, robustness, stochastic methods |
| [arXiv 2025-11-01](https://arxiv.org/abs/2511.00674) | Isotropic Curvature Model for Understanding Deep Learning Optimization: Is Gradient Orthogonalization Optimal? | curvature model, isotropy, gradient orthogonalization, optimality, theory |
| [arXiv 2025-10-31](https://arxiv.org/abs/2510.27403) | FedMuon: Accelerating Federated Learning with Matrix Orthogonalization | federated learning, matrix orthogonalization, acceleration, distributed training, Muon |
| [arXiv 2025-10-29](https://arxiv.org/abs/2503.20762) | ASGO: Adaptive Structured Gradient Optimization | structured gradients, adaptive optimization, matrix updates, efficiency, optimizer design |
| [arXiv 2025-10-28](https://arxiv.org/abs/2510.25000) | What Really Matters in Matrix-Whitening Optimizers? | matrix whitening, optimizer ablations, preconditioning, training efficiency, Muon comparison |
| [arXiv 2025-10-25](https://arxiv.org/abs/2505.24749) | SUMO: Subspace-Aware Moment-Orthogonalization for Accelerating Memory-Efficient LLM Training | subspace-aware optimization, moment orthogonalization, memory efficiency, LLM training, acceleration |
| [arXiv 2025-10-22](https://arxiv.org/abs/2510.19933) | Beyond the Ideal: Analyzing the Inexact Muon Update | inexact updates, polar approximation, robustness, theory, practical Muon |
| [arXiv 2025-10-22](https://arxiv.org/abs/2510.19376) | Optimization Benchmark for Diffusion Models on Dynamical Systems | diffusion models, dynamical systems, optimizer benchmark, scientific ML, Muon comparison |
| [arXiv 2025-10-20](https://arxiv.org/abs/2510.17802) | Unbiased Gradient Low-Rank Projection | low-rank projection, unbiased gradients, matrix optimization, memory efficiency, training |
| [arXiv 2025-10-16](https://arxiv.org/abs/2506.04430) | Leveraging Coordinate Momentum in SignSGD and Muon: Memory-Optimized Zero-Order | coordinate momentum, SignSGD, zero-order optimization, memory efficiency, Muon |
| ⭐ [arXiv 2025-10-09](https://arxiv.org/abs/2502.17410) | COSMOS: A Hybrid Adaptive Optimizer for Memory-Efficient Training of LLMs | hybrid optimizer, memory efficiency, LLM training, adaptive methods, Muon comparison |
| [arXiv 2025-10-09](https://arxiv.org/abs/2508.16067) | Training a Foundation Model for Materials on a Budget | materials foundation model, budget training, scientific ML, optimizer application, efficiency |
| [arXiv 2025-10-08](https://arxiv.org/abs/2510.06627) | POME: Post Optimization Model Edit via Muon-style Projection [[code](https://github.com/NUS-HPC-AI-Lab/POME)] | model editing, projection, post-optimization, Muon-style updates, code |
| [arXiv 2025-10-04](https://arxiv.org/abs/2510.03866) | On Provable Benefits of Muon in Federated Learning | federated learning, provable benefits, matrix orthogonalization, convergence, distributed optimization |
| [arXiv 2025-10-04](https://arxiv.org/abs/2510.03691) | REG: A Regularization Optimizer for Robust Training Dynamics | regularization optimizer, robust dynamics, row-column scaling, AdamW compatibility, Muon comparison |
| [arXiv 2025-10-02](https://arxiv.org/abs/2509.23500) | Beyond Outliers: A Study of Optimizers Under Quantization | quantized training, optimizer robustness, outliers, low precision, Muon comparison |
| [arXiv 2025-10-02](https://arxiv.org/abs/2510.02239) | Drop-Muon: Update Less, Converge Faster | sparse updates, efficiency, convergence speed, update skipping, Muon variant |
| [arXiv 2025-09-30](https://arxiv.org/abs/2509.24218) | Conda: Column-Normalized Adam for Training Large Language Models Faster | column normalization, Adam variant, LLM pretraining, speed, matrix structure |
| [arXiv 2025-09-22](https://arxiv.org/abs/2509.18396) | Development of Deep Learning Optimizers: Approaches, Concepts, and Update Rules | optimizer survey, update rules, deep learning, taxonomy, Muon context |
| [arXiv 2025-09-19](https://arxiv.org/abs/2509.15874) | ENSAM: an efficient foundation model for interactive segmentation of 3D medical images | 3D segmentation, medical imaging, foundation model, efficiency, optimizer application |
| [arXiv 2025-09-16](https://arxiv.org/abs/2509.13081) | Shaping Explanations: Semantic Reward Modeling with Encoder-Only Transformers for GRPO | reward modeling, GRPO, encoder-only transformers, explanations, optimizer application |
| [arXiv 2025-09-06](https://arxiv.org/abs/2509.02981) | AdaGrad Meets Muon: Adaptive Stepsizes for Orthogonal Updates | AdaGrad, adaptive stepsizes, orthogonal updates, optimizer theory, matrix geometry |
| [arXiv 2025-09-01](https://arxiv.org/abs/2509.01440) | Benchmarking Optimizers for Large Language Model Pretraining | optimizer benchmark, LLM pretraining, fair tuning, scale study, AdamW comparison |
| [arXiv 2025-07-17](https://arxiv.org/abs/2507.13338) | Training Transformers with Enforced Lipschitz Constants | Lipschitz constraints, transformers, stability, spectral control, optimization |
| [arXiv 2025-06-24](https://arxiv.org/abs/2506.19697) | Outlier-Safe Pre-Training for Robust 4-Bit Quantization of Large Language Models | 4-bit quantization, outlier safety, pretraining, robustness, optimizer interaction |
| [arXiv 2025-06-06](https://arxiv.org/abs/2502.07529) | Training Deep Learning Models with Norm-Constrained LMOs | norm-constrained LMO, deep learning, Frank-Wolfe, constrained optimization, Muon theory |
| ⭐ [arXiv 2025-06-01](https://arxiv.org/abs/2502.02900) | A Note on the Convergence of Muon | convergence, theoretical analysis, matrix updates, nonconvex optimization, Muon foundations |
| [arXiv 2025-05-29](https://arxiv.org/abs/2505.23884) | Test-Time Training Done Right | test-time training, adaptation, robustness, optimizer application, evaluation |
| ⭐ [arXiv 2025-05-20](https://arxiv.org/abs/2505.02222) | Practical Efficiency of Muon for Pretraining | practical efficiency, pretraining, throughput, tuning, Muon evaluation |
| ★ ⭐ [ICML 2026](https://icml.cc/Downloads/2026); [arXiv 2025-05-19](https://arxiv.org/abs/2505.13416) | From Muon to Gluon: Bridging Theory and Practice of LMO-based Optimizers for LLMs | Gluon, Scion, LMO optimizers, theory-practice gap, LLMs |
| [arXiv 2025-05-08](https://arxiv.org/abs/2505.04005) | Iterative Orthogonalization Scaling Laws | orthogonalization, scaling laws, Newton-Schulz, approximation quality, training efficiency |
| [arXiv 2025-04-30](https://arxiv.org/abs/2501.18972) | BCAT: A Block Causal Transformer for PDE Foundation Models for Fluid Dynamics | PDE foundation models, block causal transformer, fluid dynamics, optimizer application, scientific ML |
| [arXiv 2025-04-22](https://arxiv.org/abs/2504.16041) | Muon Optimizer Accelerates Grokking | grokking, generalization dynamics, training acceleration, toy tasks, Muon |
| [arXiv 2025-04-11](https://arxiv.org/abs/2504.08451) | Muon-Accelerated Attention Distillation for Real-Time Edge Synthesis via Optimized Latent Diffusion | attention distillation, edge synthesis, latent diffusion, real-time generation, optimizer application |
| [arXiv 2025-04-08](https://arxiv.org/abs/2503.12645) | Understanding Gradient Orthogonalization for Deep Learning via Non-Euclidean Trust-Region Optimization | trust region, non-Euclidean geometry, gradient orthogonalization, theory, Muon |
| ⭐ [arXiv 2025-02-24](https://arxiv.org/abs/2502.16982) | Muon is Scalable for LLM Training [[code](https://github.com/MoonshotAI/Moonlight)] | LLM training, scalability, Moonlight, optimizer engineering, large-scale evaluation |
| [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5514039) | AuON: A Survey For Linear-time Orthogonal Optimizer | survey, orthogonal optimizers, linear-time methods, Muon family, optimizer taxonomy |

### 2024

| Status | Title | Keywords |
| --- | --- | --- |
| ⭐ [URL](https://kellerjordan.github.io/posts/muon/) | Muon: An optimizer for hidden layers in neural networks | original Muon, hidden layers, orthogonalized momentum, Newton-Schulz, optimizer recipe |
