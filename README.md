# 7T SC qMRI Code

This repository gathers Python-based tools and models developed for the **reconstruction, processing, analysis, and quantification** of MRI and MRS data acquired in the human spinal cord at **7 Tesla**, as part of the 7T SC qMRI project.



## Code Contributions

| Contribution  | Repository | Description |
|------------------|----------------|----------------|
| 📈 Spectroscopy | [`PASTIS`](https://github.com/tngrssl/pastis) | Toolbox to reconstruct, process, and quantify spinal cord MRS data at 7T. Includes motion detection and correction features. |
| 🩸 Perfusion (DSC) | [`7T-DSC-MRI-Toolbox`](https://github.com/slevyrosetti/7T-DSC-MRI-Toolbox) | Functions and pipeline for processing Dynamic Susceptibility Contrast (DSC) MRI data acquired in the spinal cord at 7T. |
| 💧 Perfusion (IVIM) | [`ivim-toolbox`](https://github.com/slevyrosetti/ivim-toolbox) | Toolbox for IVIM model fitting and simulation. Developed to estimate spinal cord perfusion metrics. |
| 🤖 Segmentation | [`gm_sc_7t_t2star`](https://github.com/ivadomed/model_seg_gm-wm_t2star_7t_unet3d-multiclass) | Deep learning model (multiclass 2D U-Net) for segmentation of gray matter and spinal cord in T2*-weighted images at 7T. |
| 🧠 Template | [`AMU7T`](https://github.com/spinalcordtoolbox/template_AMU7T) | High-resolution quantitative template of the spinal cord at 7T (T1 and T2*-weighted), aligned with PAM50 space and including white/gray matter and substructure labels. |

---

## Related Projects

- 📄 [7T-SC-qMRI-protocol](https://github.com/crmbm-spinalcord/7T-SC-qMRI-protocol) – MRI protocol and SOP  
- 📦 [7T-SC-qMRI-data](https://github.com/crmbm-spinalcord/7T-SC-qMRI-data) – Representative dataset for testing and development  

---
