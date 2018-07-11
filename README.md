# hdf5
## hdf5_generator_v0.01.ipynb
* This project will help you to generate hdf5 file.
* This codes can change & merge all images you input into "one" hdf5 file
* The image size of inside of the file will be fixed 64x64 (you can manipulate the size)
* This code will display how to generate training set, test set of images for your model
* You can load the images(converted size) from the hdf5 file (see hdf5_load.ipynb)

## hdf5_load_v0.01.ipynb
* can load the file and see images it has

## import info
* from PIL import Image
* from resizeimage import resizeimage 
* import numpy as np
* import os
* import matplotlib.pyplot as plt
* %matplotlib inline
* import h5py
