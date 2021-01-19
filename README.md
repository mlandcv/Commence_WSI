# Commence_WSI
This repository aims at getting oneself started with playing around on Wholeslide Images (WSI) on Windows10.

# Installing openslide-python
We will install openslide-python in an Anaconda Environment.

Install Anaconda by following the link provided
https://www.anaconda.com/products/individual

After successful installation, create an environment using conda prompt and Python>=3:
conda create -n envname python=3.6
activate envname

Next, install other required packages and dependencies:
pip install -U matplotlib numpy openslide-python Pillow scikit-image scikit-learn scikit-image scipy Flask

Download 64-bit openslide windows binary from the following link:
https://openslide.org/download/

Extract the folder in your preferred directory and add the path for the bin folder to the windows environment variables.
I guess we are all set for a while now.




