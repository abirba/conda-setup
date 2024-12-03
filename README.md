# Description
Tested on my Mac M4 on 03/12/2024. This describes how to correctly install needed packages for Machine Learning projects, including tensorflow and tensorflow-metal.

# Prerequisites 
Install miniconda (or equivalent) corresponding to the version of Python you want to use (Python3.12 in my case). Take the MacOSX-arm64 pkg for Apple Silicon Macs. Address: https://repo.anaconda.com/miniconda/

# Packages install
After miniconda installation succeeds, create a new conda environment with the following command:
`conda env create -f tensorflow.yml -n tf-metal`, using the tensorflow.yml file in this repo. If there is no error, activate it using `conda activate tf-metal`. Check that Tensorflow is correctly installed by launching a python console and doing an `import tensorflow as tf`, it should take some time but return without any errors.
