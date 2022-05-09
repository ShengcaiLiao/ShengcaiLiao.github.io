## Kernel Sparse Representation with Local Image Features For Face Recognition

Cuicui Kang, Shengcai Liao, Shiming Xiang, and Chunhong Pan

### Introduction

We propose a novel kernel SRC framework and utilize effective local image features in this framework for robust face recognition. First, we present a kernel coordinate descent (KCD) algorithm for the l1-norm minimization problem in the kernel space, and we successfully integrate the proposed KCD algorithm in the SRC framework (called KCD-SRC) for face recognition. Second, we employ local image features and develop both pixel-level and region-level kernels for KCD-SRC based face recognition, making it discriminative and robust against illumination variations and occlusions. The region-level kernel is based on the popular Local Binary Pattern (LBP) histograms, including the Chi-Square distance based and the histogram intersection distance based kernels. We also propose a pixel-level kernel called Pixelwise Ordinal Kernel (POK). Based on pixelwise ordinal relationships and the XOR operator, POK is more effective in matching local details of two images.

### Source Codes

MATLAB functions for pixelwise ordinal features, pixelwise ordinal kernel, kernel coordinate decent l1 solver, and the kernel sparse representation based classification algorithm. [[download](https://1drv.ms/u/s!AtFUxkZAZIU-bpjOJhb6HMv-IWw)]

Please cite our Neurocomputing paper [2] if you used these codes.

### Publications

[1] Cuicui Kang, Shengcai Liao, Shiming Xiang, and Chunhong Pan. “Kernel Sparse Representation with Local Patterns for Face Recognition.” In Proceedings of the IEEE International Conference on Image Processing (ICIP 2011), Brussels, Belgium, September 11-14, 2011. [[pdf](../doc/kang-icip-2011-kernelsparselbp.pdf)]

[2] Cuicui Kang, Shengcai Liao, Shiming Xiang, and Chunhong Pan. “Kernel Sparse Representation With Pixel-level and Region-level Image Feature Kernels For Face Recognition”, Neurocomputing, Volume 133, Pages 141-152, 2014. [[pdf](../doc/kang-neucom-2014-kcdsrc-pok.pdf)] [[supplementary](../doc/kang-neucom-2014-kcdsrc-pok-sup.pdf)]
