# Principal Component Analysis

PLEASE INSTALL ASTROCONDA FOR RUNNING THIS CODE

PCA is a widely used tool for analysing big data files. In this case, we will use it to analyze the spectra in a MIRI/NIRSpec hyperrspectral cube.

We will see three diferent kinds of analysis: 

The first one is a pretty simple comparative between gaussians and spectral lines to find weird spectra. 

The second code will show you how to clean the spectra and how three spectral intensities can be linearly fitted in order to understand the 3D representation of the data.

The final step is the PCA analysis, withe the cleaning of the spectra. You will see how the spectra can be separated in clusters, and substract the linear dependance with the Principal component variables, which can be used to identify special parameters in the spectra, for example, separate the spectra with different concentrations of an specific molecule, which is present in the spectral range studied. For example in this case we remove some lines and see how we can easily differenciate two clusters.

Code made by : Pablo Rodriguez Ovalle.
In PCA (III) part of the code is taken from https://github.com/dataprofessor/code/blob/master/python/PCA_analysis.ipynb , a code used for study the iris.txt, widely used in Machine Learning classes.
