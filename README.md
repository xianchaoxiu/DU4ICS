# Deep Unrolling for Image Compressive Sensing


We currently focus on deep unfolding methods for image compressive sensing including
- [Surveys](#Surveys)
- [Parameter Learning](#PL)
- [Structure Learning](#SL)
- [Generative Learning](#GL)
- [Others](#Others)

> [!IMPORTANT]
> Last Update: 2026/08/12 


<a id="Surveys"></a>

## Surveys

- [2025] Deep Unfolding: Recent Developments, Theory, and Design Guidelines [[Paper](https://arxiv.org/abs/2512.03768)]
- [2025] 人工智能中的生成式方法：数学模型、优化算法及其应用, ORT [[Paper](https://www.ort.shu.edu.cn/CN/abstract/abstract21511.shtml)]
- [2024] Learning to Optimize: A Tutorial for Continuous and Mixed-Integer Optimization, SCCM [[Paper](https://doi.org/10.1007/s11425-023-2293-3)]
- [2023] Image Denoising: The Deep Learning Revolution and Beyond—A Survey Paper, SIIMS [[Paper](https://doi.org/10.1137/23m1545859)]
- [2023] Learned Reconstruction Methods with Convergence Guarantees: A Survey of Concepts and Applications, IEEE SPM [[Paper](https://doi.org/10.1109/msp.2022.3207451)]
- [2023] Generative Models for Inverse Imaging Problems: From Mathematical Foundations to Physics-Driven Applications, IEEE SPM [[Paper](https://doi.org/10.1109/msp.2022.3215282)]
- [2022] Theoretical Perspectives on Deep Learning Methods in Inverse Problems, IEEE JSAIT [[Paper](https://doi.org/10.1109/jsait.2023.3241123)]
- [2021] Algorithm Unrolling: Interpretable, Efficient Deep Learning for Signal and Image Processing, IEEE SPM [[Paper](https://doi.org/10.1109/msp.2020.3016905)]
- [2020] Image Reconstruction: From Sparsity to Data-Adaptive Methods and Machine Learning, PROC [[Paper](https://doi.org/10.1109/jproc.2019.2936204)]
- [2019] Solving Inverse Problems Using Data-Driven Models, AN [[Paper](https://doi.org/10.1017/s0962492919000059)]

<a id="PL"></a>

## Parameter Learning

- [2025] How to Warm-Start Your Unfolding Network, SampTA [[Paper](https://arxiv.org/abs/2502.01854)]
- [2024] Optimization Guarantees of Unfolded ISTA and ADMM Networks with Smooth Soft-Thresholding, IEEE TSP [[Paper](https://doi.org/10.1109/tsp.2024.3412981)]
- [2024] Robust Stochastically-Descending Unrolled Networks, IEEE TSP [[Paper](https://doi.org/10.1109/tsp.2024.3489223)]
- [2023] Generalization Error Bounds for Iterative Recovery Algorithms Unfolded as Neural Networks, IMAIAI [[Paper](https://doi.org/10.1093/imaiai/iaad023)]
- [2022] Compressive Sensing and Neural Networks from a Statistical Learning Perspective, CSIP [[Paper](https://doi.org/10.1007/978-3-031-09745-4_8)]
- [2021] Hyperparameter Tuning Is All You Need for LISTA, NeurIPS [[Paper](https://arxiv.org/abs/2110.15900)] [[Code](https://github.com/VITA-Group/HyperLISTA)]
- [2020] Sparse Coding with Gated Learned ISTA, ICLR [[Paper](https://openreview.net/forum?id=BygPO2VKPH)]
- [2019] ALISTA: Analytic Weights Are as Good as Learned Weights in LISTA, ICLR [[Paper](https://openreview.net/forum?id=B1lnzn0ctQ)] [[Code](https://github.com/VITA-Group/ALISTA)]
- [2019] Learning Step Sizes for Unfolded Sparse Coding, NeurIPS [[Paper](https://proceedings.neurips.cc/paper/2019/hash/d073bb8d0c47f317dd39de9c9f004e9d-Abstract.html)]
- [2018] Theoretical Linear Convergence of Unfolded ISTA and Its Practical Weights and Thresholds, NeurIPS [[Paper](https://proceedings.neurips.cc/paper/2018/hash/cf8c9be2a4508a24ae92c9d3d379131d-Abstract.html)] [[Code](https://github.com/VITA-Group/LISTA-CPSS)]
- [2017] Understanding Trainable Sparse Coding with Matrix Factorization, ICLR [[Paper](https://openreview.net/forum?id=SJGPL9Dex)]
- [2010] Learning Fast Approximations of Sparse Coding, ICML [[Paper](https://dl.acm.org/doi/abs/10.5555/3104322.3104374)]

<a id="SL"></a>

## Structure Learning

- [2026] Deep Unfolding ADMM Network for CS Image Reconstruction with Long-Short Term Residuals, SP [[Paper](https://doi.org/10.1016/j.sigpro.2025.110450)]
- [2026] MP-DUN: Manifold Prior Based Deep Unfolding Network for Image Compressed Sensing, KBS [[Paper](https://doi.org/10.1016/j.knosys.2025.115157)] [[Code](https://github.com/nkbourne/MP-DUN)]
- [2026] Beyond Single Solution: Multi-Hypothesis Collaborative Deep Unfolding Network for Image Compressive Sensing, CVPR [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Cui_Beyond_Single_Solution_Multi-Hypothesis_Deep_Unfolding_Network_for_Image_Compressive_CVPR_2026_paper.html)]
- [2026] Multi-Scale Gradient-Guided Unrolling Architecture with Adaptive Mamba for Compressive Sensing, CVPR [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_Multi-Scale_Gradient-Guided_Unrolling_Architecture_with_Adaptive_Mamba_for_Compressive_Sensing_CVPR_2026_paper.html)] [[Code](https://github.com/nikou-arch/MambaCS)]
- [2025] PLV-CSNet: Projected Landweber Variant Unfolding Network for Image Compressive Sensing Reconstruction, NEUCOM [[Paper](https://doi.org/10.1016/j.neucom.2025.129723)] [[Code](https://github.com/junp-hao/PLV-CSNet)]
- [2025] RCMFDUN: Deep Unfolding Network with Range-Nullspace Decomposition and Multi-Scale Feature Fusion for High-Fidelity Compressed Sensing, NEUCOM [[Paper](https://doi.org/10.1016/j.neucom.2025.131719)]
- [2025] A Novel Transmission-Augmented Deep Unfolding Network with Consideration of Residual Recovery, CIS [[Paper](https://doi.org/10.1007/s40747-024-01727-2)]
- [2025] Proximal Algorithm Unrolling: Flexible and Efficient Reconstruction Networks for Single-Pixel Imaging, CVPR [[Paper](https://doi.org/10.1109/cvpr52734.2025.00047)] [[Code](https://github.com/pwangcs/ProxUnroll)]
- [2025] HUNet: Homotopy Unfolding Network for Image Compressive Sensing, CVPR [[Paper](https://doi.org/10.1109/cvpr52734.2025.01194)] [[Code](https://github.com/ICSResearch/HUNet)]
- [2025] Generalization Analysis of an Unfolding Network for Analysis-Based Compressed Sensing, ACHA [[Paper](https://doi.org/10.1016/j.acha.2025.101787)] [[Code](https://github.com/vicky-k-19/deconet)]
- [2023] Generalization and Estimation Error Bounds for Model-Based Neural Networks, ICLR [[Paper](https://arxiv.org/abs/2304.09802)] [[Code](https://github.com/NeurIPS2022-Model-based-NN/Model_based_Network_Sparse_vector_recovery)]
- [2022] ADMM-DAD Net: A Deep Unfolding Network for Analysis Compressed Sensing, ICASSP [[Paper](https://doi.org/10.1109/icassp43922.2022.9747096)]
- [2021] FISTA-Net: Learning a Fast Iterative Shrinkage Thresholding Network for Inverse Problems in Imaging, IEEE TMI [[Paper](https://doi.org/10.1109/tmi.2021.3054167)] [[Code](https://github.com/jinxixiang/FISTA-Net)]
- [2021] ISTA-Net++: Flexible Deep Unfolding Network for Compressive Sensing, ICME [[Paper](https://arxiv.org/abs/2103.11554)] [[Code](https://github.com/jianzhangcs/ISTA-Netpp)]
- [2020] Optimization-Inspired Compact Deep Compressive Sensing, IEEE JSTSP [[Paper](https://doi.org/10.1109/jstsp.2020.2977507)] [[Code](https://github.com/jianzhangcs/OPINE-Net)]
- [2020] ADMM-CSNet: A Deep Learning Approach for Image Compressive Sensing, IEEE TPAMI [[Paper](https://doi.org/10.1109/tpami.2018.2883941)] [[Code](https://github.com/yangyan92/ADMM-CSNet)]
- [2018] ISTA-Net: Interpretable Optimization-Inspired Deep Network for Image Compressive Sensing, CVPR [[Paper](https://doi.org/10.1109/cvpr.2018.00196)] [[Code](https://github.com/jianzhangcs/ISTA-Net)]
- [2018] Learned Primal-Dual Reconstruction, IEEE TMI [[Paper](https://doi.org/10.1109/tmi.2018.2799231)] [[Code](https://github.com/adler-j/learned_primal_dual)]
- [2017] A Primal Dual Network for Low-Level Vision Problems, GCPR [[Paper](https://doi.org/10.1007/978-3-319-66709-6_16)]
- [2017] Learned D-AMP: Principled Neural Network Based Compressive Image Recovery, NeurIPS [[Paper](https://arxiv.org/abs/1704.06625)] [[Code](https://github.com/ricedsp/D-AMP_Toolbox)]
- [2016] Deep ADMM-Net for Compressive Sensing MRI, NeurIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2016/hash/1679091c5a880faf6fb5e6087eb1b2dc-Abstract.html)] [[Code](https://github.com/yangyan92/Deep-ADMM-Net)]

<a id="GL"></a>

## Generative Learning

- [2026] Error Analysis of Bayesian Inverse Problems with Generative Priors [[Paper](https://arxiv.org/abs/2601.17374)]
- [2026] P-Flow: Proxy-Gradient Flows for Linear Inverse Problems [[Paper](https://arxiv.org/abs/2605.08328)]
- [2025] Flow-Matching Guided Deep Unfolding for Hyperspectral Image Reconstruction [[Paper](https://arxiv.org/abs/2510.01912)] [[Code](https://github.com/YiAi03/FMU)]
- [2025] Using Powerful Prior Knowledge of Diffusion Model in Deep Unfolding Networks for Image Compressive Sensing, CVPR [[Paper](https://doi.org/10.1109/cvpr52734.2025.01677)] [[Code](https://github.com/FengodChen/DMP-DUN-CVPR2025)]
- [2025] Latent Diffusion Prior Enhanced Deep Unfolding for Snapshot Spectral Compressive Imaging, ECCV [[Paper](https://doi.org/10.1007/978-3-031-73414-4_10)] [[Code](https://github.com/Zongliang-Wu/LADE-DUN)]
- [2025] Deep Unfolding Architecture Based on Generative Prior Diffusion for Image Compressive Sensing, IEEE SPL [[Paper](https://doi.org/10.1109/lsp.2025.3586178)] [[Code](https://github.com/nkbourne/GPD-CS)]
- [2025] Diff-Unfolding: A Model-Based Score Learning Framework for Inverse Problems [[Paper](https://arxiv.org/abs/2505.11393)]
- [2024] Flow Priors for Linear Inverse Problems via Iterative Corrupted Trajectory Matching, NeurIPS [[Paper](https://arxiv.org/abs/2405.18816)] [[Code](https://github.com/YasminZhang/ICTM)]
- [2024] Regularising Inverse Problems with Generative Machine Learning Models, JMIV [[Paper](https://doi.org/10.1007/s10851-023-01162-x)]
- [2023] Diffusion Posterior Sampling for General Noisy Inverse Problems, ICLR [[Paper](https://arxiv.org/abs/2209.14687)] [[Code](https://github.com/DPS2022/diffusion-posterior-sampling)]
- [2023] Pseudoinverse-Guided Diffusion Models for Inverse Problems, ICLR [[Paper](https://openreview.net/forum?id=9_gsMA8MRKQ)]
- [2023] Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model, ICLR [[Paper](https://arxiv.org/abs/2212.00490)] [[Code](https://github.com/wyhuai/DDNM)]
- [2022] Solving Inverse Problems by Joint Posterior Maximization with Autoencoding Prior, SIIMS [[Paper](https://doi.org/10.1137/21m140225x)]
- [2022] Denoising Diffusion Restoration Models, NeurIPS [[Paper](https://arxiv.org/abs/2201.11793)] [[Code](https://github.com/bahjat-kawar/ddrm)]
- [2022] Image Denoising with Deep Unfolding and Normalizing Flows, ICASSP [[Paper](https://doi.org/10.1109/icassp43922.2022.9747748)]
- [2022] Deep Unfolding with Normalizing Flow Priors for Inverse Problems, IEEE TSP [[Paper](https://doi.org/10.1109/tsp.2022.3179807)]
- [2021] Composing Normalizing Flows for Inverse Problems, ICML [[Paper](https://proceedings.mlr.press/v139/whang21b.html)]
- [2020] Solving Inverse Problems via Auto-Encoders, IEEE JSAIT [[Paper](https://doi.org/10.1109/jsait.2020.2983643)]
- [2017] Compressed Sensing Using Generative Models, ICML [[Paper](https://arxiv.org/abs/1703.03208)] [[Code](https://github.com/AshishBora/csgm)]

<a id="Others"></a>

## Others

- [2026] STAR-Net: An Interpretable Model-Aided Network for Remote Sensing Image Denoising, PR [[Paper](https://doi.org/10.1016/j.patcog.2025.112496)] [[Code](https://github.com/Jason011212/STAR-Net)]
- [2026] A Constrained Optimization Perspective of Unrolled Transformers, ICML [[Paper](https://arxiv.org/abs/2601.17257)]
- [2026] Deep LoRA-Unfolding Networks for Image Restoration, IEEE TIP [[Paper](https://arxiv.org/abs/2602.18697)]
- [2025] DeepSN-Net: Deep Semi-Smooth Newton Driven Network for Blind Image Restoration, IEEE TPAMI [[Paper](https://doi.org/10.1109/tpami.2024.3525089)] [[Code](https://github.com/pandazcx/DeepSN-Net)]
- [2025] Deep Semi-Smooth Newton-Driven Unfolding Network for Multi-Modal Image Super-Resolution, IEEE TIP [[Paper](https://doi.org/10.1109/tip.2025.3625429)] [[Code](https://github.com/pandazcx/SNUM-Net)]
- [2025] Lightweight Deep Unfolding Networks with Enhanced Robustness for Infrared Small Target Detection [[Paper](https://arxiv.org/abs/2509.08205)] [[Code](https://github.com/xianchaoxiu/L-RPCANet)]
- [2025] Vision-Language Gradient Descent-Driven All-In-One Deep Unfolding Networks, CVPR [[Paper](https://doi.org/10.1109/cvpr52734.2025.00705)] [[Code](https://github.com/xianggkl/VLU-Net)]
- [2021] Global and Quadratic Convergence of Newton Hard-Thresholding Pursuit, JMLR [[Paper](https://jmlr.org/papers/v22/19-026.html)]
- [2021] Deep Equilibrium Architectures for Inverse Problems in Imaging, IEEE TCI [[Paper](https://doi.org/10.1109/tci.2021.3118944)] [[Code](https://github.com/dgilton/deep_equilibrium_inverse)]
- [2017] The Little Engine That Could: Regularization by Denoising, SIIMS [[Paper](https://doi.org/10.1137/16m1102884)]
- [2014] Proximal Algorithms, FnT OPT [[Paper](https://doi.org/10.1561/2400000003)]
- [2013] Plug-And-Play Priors for Model-Based Reconstruction, GlobalSIP [[Paper](https://doi.org/10.1109/globalsip.2013.6737048)] [[Code](https://github.com/svvenkatakrishnan/plug-and-play-priors)]
- [2011] Distributed Optimization and Statistical Learning via the Alternating Direction Method of Multipliers, FnT ML [[Paper](https://doi.org/10.1561/9781601984616)]
- [2011] A First-Order Primal-Dual Algorithm for Convex Problems with Applications to Imaging, JMIV [[Paper](https://doi.org/10.1007/s10851-010-0251-1)]
- [2010] Large-Scale Machine Learning with Stochastic Gradient Descent, COMPSTAT [[Paper](https://doi.org/10.1007/978-3-7908-2604-3_16)]
- [2009] A Fast Iterative Shrinkage-Thresholding Algorithm for Linear Inverse Problems, SIIMS [[Paper](https://doi.org/10.1137/080716542)]
- [2009] Message-Passing Algorithms for Compressed Sensing, PNAS [[Paper](https://doi.org/10.1073/pnas.0909892106)]
- [2001] Convergence of a Block Coordinate Descent Method for Nondifferentiable Minimization, JOTA [[Paper](https://doi.org/10.1023/a:1017501703105)]


