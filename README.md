# Granularity-guided-deep-learning-for-precise-Cryptosporidium-parasite-image-analysis




## Overview
 We propose a coarse-to-fine segmentation approach to precisely segment a population of Cryptosporidium parvum parasites from a microscopic image by the first step. Then, a subsequent classifier with high discriminatory power is used to distinguish the life stages of the parasites among 4 asexual stages: oocyst, trophozoite, meront, and free form. To the best of our knowledge, this work is the first to address Cryptosporidium parvum analysis from microscopic images and offers a precision tool for assisting the biologists.  
 
<div align=center> 
 <img src="https://github.com/jtyytim/CryptosporidiumNet/blob/main/Overview.png" width="900px">
 
Fig 1. An overview of our proposed framework for Cryptosporidium parasite image analysis. 
</div>

## Data
 Our dataset for the analysis Cryptosporidium parvum comprises 58 microscopic images. The images have been obtained by infection of HCT-8 cell lines with Cryptosporidium parvum in the laboratory (24 hours of infection) and staining them using specific fluorescent markers. The stained parasites can be visible in the green channel of microscope. In the life cycle of Cryptosporidium parvum, we studied the asexual stage, containing four species: oocyst, trophozoite, meront, and free form. All images have been manually annotated by a parasitologist to delimit the outline of each parasite (as shown in the following image).
 
<div align=center> 
 <img src="https://github.com/jtyytim/CryptosporidiumNet/blob/main/Annotation.png" width="400px">
 
Fig 2. Example of parasite image annotated by biologist using 4 different colors. 
</div>

## Usage
 Steps:
 - Install required libraries (read Requirements.txt file for more details)
 - Download the project (repository) and unzip it, then you can find all the jupyter notebooks in file "Codes" for different tasks (segmentation and classification) and some test data in file "Data".
 - Find the Drive link in file "Download models" and download all the models.
 - Before running the code, please make sure that the data and model are in the right place as indicated in each jupyter notebook.
 
 ## Report
 [A report for the experimental performance](https://github.com/jtyytim/CryptosporidiumNet/blob/main/Experimental%20performance.pdf)

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
