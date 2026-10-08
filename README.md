# RePrior: Measurement-Reconciled Prior Correction for Sparse-View CBCT Reconstruction

**Research project | Under review at ICLR 2027**

RePrior is a progressive, measurement-constrained prior-correction framework for sparse-view cone-beam computed tomography (CBCT) reconstruction. It transfers complementary 3D anatomical information from learned volumetric priors into patient-specific Gaussian reconstruction, while checking compatibility with the acquired X-ray projections.

## Method

RePrior consists of three complementary components:

1. **Selective Correction Proposal (SCP)** identifies actionable local differences between a learned volumetric prior and a prior-assisted Gaussian reconstruction.
2. **Measurement-Constrained Reconciliation (MCR)** jointly reconciles candidate corrections according to their patient-specific X-ray projection responses.
3. **Hybrid Residual Enhancement (HRE)** uses bounded voxel- and Gaussian-domain residual updates to recover further corrections while respecting measurement constraints.

## Results

The submission reports an approximately **2.63 dB macro-average improvement in 3D PSNR over R²-Gaussian** on LUNA16, PANORAMA, and PENGWIN in its matched experimental setting.

The project page is being prepared with the anonymous manuscript, method overview, reconstruction comparisons, and supplementary 3D reconstruction video.

## Code Availability

**The code will be released upon acceptance of the paper.**

The code is not publicly available at this stage.

## Project Website

A minimalist academic project page is being prepared for GitHub Pages.

## Acknowledgement of Website Template

The project-page layout is adapted from [3DSceneEditor](https://ziyangyan.github.io/3DSceneEditor/) and [Nerfies](https://nerfies.github.io/). The source website's applicable attribution and licensing requirements should be retained when its template files are published.
