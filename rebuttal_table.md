### Table A. Quantitative comparison (PSNR/SSIM) with state-of-the-art methods under Gaussian noise (σ = 25).

> **Bold** = best, _italic_ = second-best

| Dataset   | Noisy        | AP-BSN        | PUCA         | UGoDIT       | SITCOM       |      Neb2Neb      | SHIELD-PR (Neb2Neb) | N2N           | SHIELD-PR (N2N) |
|-----------|-------------|--------------|-------------|-------------|-------------|-------------|---------------------|--------------|----------------|
| Tampere17 | 20.44/0.416 | 25.91/0.703 | 26.03/0.684 | 25.91/0.670 | 25.47/0.676 | 26.92/0.700 | 28.22/0.773 | **30.32**/*0.840* | *30.19*/**0.844** |
| Kodak24   | 20.44/0.350 | 25.16/0.692 | 25.49/0.675 | 27.20/0.699 | 24.57/0.627 | 27.06/0.678 | 28.35/0.756 | **30.82**/*0.838* | *30.58*/**0.839** |
| Set14     | 20.59/0.436 | 22.67/0.644 | 22.13/0.602 | 24.45/0.625 | 25.16/0.707 | 26.50/0.724 | 26.43/0.748 | *28.57*/*0.813* | **28.67**/**0.824** |

### Table B. Quantitative comparison on synthetic (Rain100L) and real-world (SPA) deraining datasets. PSNR/SSIM are reported for Rain100L, and NIQE/PI for SPA.
> **Bold** = best, _italic_ = second-best



### Table C. Quantitative comparison (PSNR/SSIM) under mixed degradation settings. We evaluate inpainting (50\% random mask) + Gaussian noise ($\sigma=25$) and super-resolution ($\times2$) + Gaussian noise ($\sigma=25$). 

> **Bold** = best, *italic* = second-best

| Tasks      | Datasets   | degradation | Dense        | SHIELD-P     | SHIELD-R         | SHIELD-PR         |
|------------|------------|-------------|--------------|--------------|------------------|-------------------|
| Inpainting | Tampere17  | 8.67/0.140 | 26.70/0.702 | 26.87/0.721 | **27.30**/*0.728* | *27.20*/**0.730** |
|            | Kodak24    | 11.40/0.136 | 25.99/0.680 | 26.08/0.687 | **26.64**/**0.709** | *26.58*/*0.708* |
| SR         | Tampere17  | 19.51/0.328 | 25.26/0.666 | 25.31/0.666 | *25.54*/*0.686* | **25.60**/**0.688** |
|            | Kodak24    | 19.22/0.244 | 24.69/0.642 | 24.75/0.648 | *24.99*/*0.659* | **25.11**/**0.660** |
