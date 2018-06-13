# Instructive IPython Notebooks
This repository will be progressively populated with IPython (or Jupyter) Notebooks (IPNBs) that I made to demonstrate theories and practices in digital image processing, Fourier optics, Python numerical computation, and Tensorflow usage. Check out the individual notebooks for more details. 

# How to view and run notebooks
Github now supports viewing IPNBs on the web interface, but you'll need to download them to your local drive in order to execute the scripts. As the first step, `git clone` this repo onto your computer hard disk.

If you are new to Python or don't know how to use IPython notebook, I recommend you to download the Anaconda distribution of Python which comes along with a easy-to-use package manager. Download the latest version of Anaconda from [here](https://www.anaconda.com/download).

Anaconda should become your default Python interpreter after installation. Now open a terminal, cd into the repo's directory and do `jupyter-notebook`. A URL containing `localhost:8888` (port number may vary) will be prompted. Open the URL in your browser and then you see the interface of IPNB. You will find that the codes in an IPNB is organized into blocks. To run a block, simply hit `Ctrl` + `Enter` with your curser in it. 

If you have packages missing, do `conda install xxx` in Terminal to get it installed. Sometimes the package name appearing in the import statements in the Python script can be different from what you should search on Conda. For example, the package imported by `import cv2` is formally called "opencv". If you can't find a package on Conda, do a Google search for it. 
