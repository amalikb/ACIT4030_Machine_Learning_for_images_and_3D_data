# ACIT4030 Machine Learning For Images and 3D Data

## Dataset Package

The project used the dataset from ModelNet40 and ShapeNet, which would result in 11GB.

Therefore, the combined dataset is stored in OsloMet Onedrive. The link can be found in the below attachment.

OneDrive Link: [ModelNet40+ShapeNet](https://hioa365-my.sharepoint.com/:f:/g/personal/s371145_oslomet_no/EmG1X7M9udFGiRuH8zP7zPABjvtgTVy4Ge6-lSa0a21cqQ)

## Script Description
The PointNet - CNN trained models were performed on different computers. All the scripts are documented in '*.ipynb*' format and stored in '*01.Submitted_Files*' folder.

Please update the directory with the corrsponding user name in order to run the script successfully!

## Python Package Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install essential packages if it is needed.
````bash 
pip install numpy
pip install pandas
pip install tensorflow
pip install trimesh
pip install matplotlib
````

After the package installation, please run this code block to initiate the procedure of loading, data parsing, training/testing and validating the models
````bash
import os
import glob
import trimesh
import numpy as np
import tensorflow as tf
from tensorflow import keras
from tensorflow.keras import layers
from matplotlib import pyplot as plt

tf.random.set_seed(1234)
````