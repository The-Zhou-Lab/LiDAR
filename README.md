# CropQuant-3D

Yulei Zhu<sup>1</sup>, Gang Sun<sup>1</sup>, Jie Zhou<sup>1</sup>, Ji Zhou<sup>1,2*</sup>

<sup>1</sup>State Key Laboratory of Crop Genetics & Germplasm Enhancement, College of Engineering, College of Agriculture, Plant Phenomics Research Center, Academy for Advanced Interdisciplinary Studies, Jiangsu Collaborative Innovation Center for Modern Crop Production Co-sponsored by Province and Ministry, Nanjing Agricultural University, Nanjing 210095, China;

<sup>2</sup>Cambridge Crop Research, National Institute of Agricultural Botany (NIAB), Cambridge CB3 0LE, UK

## Overview
In this release, we uploaded the latest version of CropQuant-3D, a graphical user interface (GUI, in .exe format) based analytic software that can be utilised to carry out 3D trait analysis on LiDAR-collected point cloud data in large-scale field phenotyping. The use of backpack LiDAR or other sources can acquire millions of 3D points to represent spatial features of crops. To effectively analyse these point clouds, CropQuant-3D was developed to extract plot-based phenotypic traits from large, complex point clouds with limited computing time and power. We combined a backpack LiDAR device and CropQuant-3D to quantify crop height, 3D canopy index (3DCI, an original 3D measurement of canopy variation), 3D canopy surface, canopy coverage and biomass estimation (i.e. 3DVI and 3DPI), in a case study examining the response of wheat varieties to three different levels of nitrogen fertilisation in field experiments. The combined solution can differentiate significant genotype and treatment effects on key performance-related morphological traits and structural variation in canopy, with strong correlations with conventional manual measurements. Hence, we believe that CropQuant-3D could be used for consistently quantifying key traits at a larger scale and more quickly than heretofore possible, which could be used as a reliable research tool and jointly developed with the plant research community for large-scale and multi-location field phenotyping in crop research and breeding activities. 


## Install Python, Anaconda and Libraries
If you wish to run CropQuant-3D from the code, you will need to set up Python on your system. 

1. Install Python releases:
   
   •	Read the beginner’s guide to Python if you are new to the language: 
   https://wiki.python.org/moin/BeginnersGuide
   
   •	For Windows users, Python 3 release can be downloaded via: 
   https://www.python.org/downloads/windows/
   
   •	Crop3D-Mobile only supports Python 3

2. Install Anaconda Python distribution:
   
   •	Read the install instruction using the URL: https://docs.continuum.io/anaconda/install
   
   •	For Windows users, a detailed step-by-step installation guide can be found via: 
   https://docs.continuum.io/anaconda/install/windows 
   
   •	An Anaconda Graphical installer can be found via: 
   https://www.continuum.io/downloads

   •	We recommend users install the latest Anaconda Python distribution

3. Install packages:

   • CropQuant-3D uses a number of 3rd-party libraries that you may need to add to your conda environment.
   These include, but are not limited to:
   
       Laspy=1.7.0
       Whitebox=1.3.0
       GDAL=3.1.4
       Rasterio=1.1.8
       Open3d=0.11.2
       mayavi=4.7.2
       Scikit-image=0.17.2
       Opencv-python=4.4.0.46
       Matplotlib =3.3.3
       Pandas=1.1.5
       Numpy=1.19.4
       Scipy=1.5.3
   
## Running CropQuant-3D

Before using the software and source code, please see the CropQuant-3D user guide.pdf file on this repository. A compressed Windows (exe format, i.e. CropQuant-3D.zip) file can be downloaded from the release link as well.
