# Granularity-guided-deep-learning-for-precise-Cryptosporidium-parasite-image-analysis




## Overview
 We propose a coarse-to-fine segmentation approach to precisely segment a population of Cryptosporidium parvum parasites from a microscopic image by the first step. Then, a subsequent classifier with high discriminatory power is used to distinguish the life stages of the parasites among 4 asexual stages: oocyst, trophozoite, meront, and free form. To the best of our knowledge, this work is the first to address Cryptosporidium parvum analysis from microscopic images and offers a precision tool for assisting the biologists.  
 
![IVGG8](https://github.com/jtyytim/CryptosporidiumNet/blob/main/Overview.png)
Fig 1. An overview of our proposed framework for Cryptosporidium parasite image analysis. 

## Data
 Our dataset for the analysis Cryptosporidium parvum comprises 58 microscopic images. The images have been obtained by infection of HCT-8 cell lines with Cryptosporidium parvum in the laboratory (24 hours of infection) and staining them using specific fluorescent markers. The stained parasites can be visible in the green channel of microscope. In the life cycle of Cryptosporidium parvum, we studied the asexual stage, containing four species: oocyst, trophozoite, meront, and free form. All images have been manually annotated by a parasitologist to delimit the outline of each parasite (as shown in the following image).
 ![IVGG8](https://github.com/jtyytim/CryptosporidiumNet/blob/main/Overview.png)
Fig 2. Example of parasite image annotated by biologist using 4 different colors. 

## How to cite
[1] Yang, Z., Benhabiles, H., Windal, F., Follet, J., Leniere, A. C., & Collard, D. (2022). A Coarse-to-Fine Segmentation Methodology Based on Deep Networks for Automated Analysis of Parasite from Fluorescence Microscopic Images. In International Workshop on Medical Optical Imaging and Virtual Microscopy Image Analysis (pp. 156-166). Springer, Cham.  
```
@inproceedings{yang2022coarse,
  title={A Coarse-to-Fine Segmentation Methodology Based on Deep Networks for Automated Analysis of Parasite from Fluorescence Microscopic Images},
  author={Yang, Ziheng and Benhabiles, Halim and Windal, Feryal and Follet, J{\'e}r{\^o}me and Leniere, Anne-Charlotte and Collard, Dominique},
  booktitle={International Workshop on Medical Optical Imaging and Virtual Microscopy Image Analysis},
  pages={156--166},
  year={2022},
  organization={Springer}
}
```
