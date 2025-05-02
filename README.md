# MRI/MRS features for processing Spinal Cord Imaging at 7T

This repository gathers various Python-based toolboxes developed for the reconstruction, processing, analysis and quantification of MRI and MRS data acquired in the human spinal cord at 7 Tesla.

| Contribution  | Repository | Description |
|----|------------|-------------|
| Spectroscopy  | [`PASTIS`](https://github.com/tngrssl/pastis) | Python toolbox originally developed to reconstruct, process, and quantify spinal cord MRS data at 7T. Includes specific features for motion detection and correction. |
|  Perfusion | [`7T-DSC-MRI-Toolbox`](https://github.com/slevyrosetti/7T-DSC-MRI-Toolbox) | Python toolbox providing functions and a pipeline to process Dynamic Susceptibility Contrast (DSC) MRI data acquired in the spinal cord at 7T. |
| Perfusion  | [`ivim-toolbox`](https://github.com/slevyrosetti/ivim-toolbox) | Python toolbox dedicated to model fitting and simulation for Intra-Voxel Incoherent Motion (IVIM) MRI. Originally developed to quantify spinal cord IVIM-based perfusion parameters. |
| Segmentation  | [`gm_sc_7t_t2star`](https://github.com/ivadomed/model_seg_gm-wm_t2star_7t_unet3d-multiclass) | Deep learning model for automatic segmentation of gray matter and spinal cord T2*-weighted images at 7T using a multiclass 2D U-Net architecture. |
| Template  | [`AMU7T`](https://github.com/spinalcordtoolbox/template_AMU7T) | High-resolution multimodal quantitative T1 and T2*-weighted templates with white and gray matter spinal cord and substructures atlas, aligned with the PAM50 space |
