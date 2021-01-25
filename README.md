# Commence_WSI
This repository aims at getting oneself started on playing around with Wholeslide Images (WSI) (Windows10).

# Installing openslide-python
Openslide can be used to read a variety of whole-slide image formats, including the .svs files. We will install openslide-python in an Anaconda Environment.

Install Anaconda by following the link provided
```
    https://www.anaconda.com/products/individual
```
After successful installation, create an environment with Python>=3 using conda prompt:
```
    conda create -n envname python=3.6
    activate envname
```
Next, install other required packages and dependencies:
```
    pip install -U matplotlib numpy openslide-python Pillow scikit-image scikit-learn scikit-image scipy Flask opencv-python
```
Download 64-bit openslide windows binary from the following link:
```
    https://openslide.org/download/
```
Extract the folder in your preferred directory and add the path for the bin folder to the windows environment variables.
I guess we are all set for a while now.

# Visualising WSI using openslide
Lets validate our installations by doing a simple task of visualising our WSI using Deepzoom python interface from the openslide repository.
Clone the following repository using git or just download it if you dont use git for windows:
```
    git clone https://github.com/openslide/openslide-python.git
    cd openslide-python/examples/deepzoom
    python deepzoom_multiserver.py -Q 100 path/to/the/WSI/data/folder
```
This will start a web interface and display the image files specified in the path to the image folder.
All good

