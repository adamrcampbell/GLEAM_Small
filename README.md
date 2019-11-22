
# GLEAM Radio Astronomy Observational Data - small data-set
---
#### Table of Contents:
1. [Introduction](####Introduction)
2. [Repository Contents](####Repository-Contents)
3. [Observational Parameters](####Observational-parameters)
4. [Sample Images](####Sample-Images)

---
#### Introduction

---
#### Repository Contents

---
#### Observational Parameters

The following observational parameters describe attributes of the observation performed during the collection of this data-set. These terms can prove useful when generating a suitable set of W-Projection convolution kernels for gridding/de-gridding of this data-set.

| | Value | Note | 
|:-------------|:-------------:|:---:|
| **Number of Recievers** | 512 | - |
| **Number of Channels** | 1 | - |
| **Sampled Frequencies (Hz)** | 1.40e+08 | Single channel |
| **Field of View** | 1 degree | Max 0.707 degree radius for deconvolution |
| **Observation Duration** | 15 minutes | - |
| **Integration Time (delta-T)** | Every 30 seconds | - |
| **Number of Time Samples** | 30 | Observation Length / delta-T |
| **Number of Baseline Sets** | 30 | Time Samples * Number of Channels|
| **Number of Recievers** | 512 | - |
| **Image Size** | 2048^2 | - |
| **Grid Size** | 2458^2 | 1.2x image size to remove edge based artifacts |
| **Number of Visibilities** | 3,924,480 | Number of Baselines * Baseline Sets * Number of Channels |
| **Number of Sky Sources** | 33 | - |
| **Number of W-Projection Kernels** | 17 | This is only a suggestion, and can be any specific number of your choosing |
| **Min W-Projection Kernel Half Support** | 4 | - |
| **Max W-Projection Kernel Half Support** | 4 | - |
| **W-Projection Kernel Oversampling** | 4 | This is only a suggestion, and can be any specific number of your choosing |
| **Max UVW** | 1895.410847844 | - |
| **Cell Size (radians)** | 8.52211548825356E-06 | - |

---
#### Sample Images
